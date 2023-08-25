Installation
============

The **spfluo-app** is availble on :ref:`Windows <windows-section>` and Linux. A GPU is recommended but not necessary.

.. _windows-section:

On Windows
----------

1. Install Python
    a. Go to the `Python download page <https://www.python.org/downloads/>`_.
    b. Download Python 3.11.
    c. Run the executable.
    d. **Important**: tick the box `Add Python to PATH`.
    e. Click `Install Now`.

2. Install **spfluo-app**
    a. Unzip `spfluo-app.zip`
    b. Open the command line interpreter. To do so:
        i. Press the keys windows + R
        ii. Enter "cmd".
    c. Once the interpreter is opened, enter the following command::

        $ cd C:\path\to\spfluo-app\spfluo-app
    
    The :command:`cd` command will move you to the desired folder.
    
    d. Enter the :command:`dir` command. Make sure the following files are present:
        - requirements-cpu.txt
        - spfluo-app.pyw
    
    e. Run the installation with the following commands:
        - If you have a GPU::

            $ py -m pip install -r requirements-gpu.txt
            $ py -m pip install -r requirements-gpu-windows.txt
        - Otherwise::

            $ py -m pip install -r requirements-cpu.txt

The installation is now done! You should now be able to double-click on the file spfluo-app.pyw. It should open the Scipion launcher.

You can create a shortcut:
    1. Right click on the file
    2. More options
    3. Send to the desktop

Hi,
I have the windows 10 Pro(win 32) installed on my computer.


Step 1
------
I want o have only one version of Python 3.7.7 on this machine

-Hystory:
---------

On this computer was many other python's versions already installed.
And in plus was and Anaconda3 installed.
Before at All I intend to remain with one single python 3.
On my computer must to remain only python 3.7.7 located in :
    "C:\Program Files\WindowsApps\PythonSoftwareFoundation.Python.3.7_3.7.2032.0_x64__qbz5n2kfra8p0"
    
Finaly intend to have:

C:\Users\{User}>python --version
Python 3.7.7

C:\Users\{User}>python
Python 3.7.7 (tags/v3.7.7:d7c567b08f, Mar 10 2020, 11:52:54) [MSC v.1900 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>CTRL+Z

So before at all must to delete all previous versions of python and Anaconda 3.
For that I used this tutorial to uninstall Anaconda 3
https://docs.anaconda.com/anaconda/install/uninstall/

            "Option A. Use simple remove to uninstall Anaconda:

            Windows
            Use Windows Explorer to delete the envs and pkgs folders prior to running the uninstall in the root of your installation.
            In the Control Panel, choose Add or Remove Programs or Uninstall a program, and then select Python 3.6 (Anaconda) or 
            your   version of Python."
            
-Action:
---------
cmd.exe

cd /path/to/Anavconda 3

rmdir envs /s

rmdir pkgs /s

cd C:\Users\{User}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\System Tools

click on Control panel and

Uninstalling all previous python versions and anaconda3.


Step 2
------

Now want to install OpenCV4 for Python 3.7(64 bit (AMD64).

For that have this tutorial: 
   https://pysource.com/2019/03/15/how-to-install-python-3-and-opencv-4-on-windows/

1. Download the Opencv binary files here: https://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv

   in my case: 
        opencv_python-4.2.0-cp37-cp37m-win_amd64.whl




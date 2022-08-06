# my-python-game

Alien Invasion! A Space Invaders rip-off.

Join our heros on their quest to defeat the never ending alien invasion.
How long can you survive?


You will need Python 3.6 (or above) and Pygame to play the game.


Installing Python:
First, check whether Python is installed on your system. 
Open a command window by entering command into the Start menu or by holding down the shift key while right-clicking on your desktop and selecting Open command window here from the menu. 
In the terminal window, enter python in lowercase. 
If you get a Python prompt (>>>) in response, Python is installed on your system. 
If you see an error message telling you that python is not a recognized command, Python isn’t installed.

In that case, or if you see a version of Python earlier than Python 3.6, you need to download a Python installer for Windows.
Go to https://python.org/ and hover over the Downloads link.
You should see a button for downloading the latest version of Python.
Click the button, which should automatically start downloading the correct installer for your system.
After you’ve downloaded the file, run the installer.
Make sure you select the option Add Python to PATH, which will make it easier to configure your system correctly.
Open a command window and enter python in lowercase.
You should see a Python prompt (>>>), which means Windows has found the version of Python you just installed.

C:\> python
Python 3.7.2 (v3.7.2:9a3ffc0492, Dec 23 2018, 23:09:28) [MSC v.1916 64 bit
(AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>

Any time you want to run a snippet of Python code, open a command window and start a Python terminal session.
To close the terminal session, press ctrl-Z and then press enter, or enter the command exit().

To install Pygame, enter the following command at a terminal prompt:
$ python -m pip install --user pygame

This command tells python to run the pip module and install the pygame package to the current user's Python installation.
If you use a command other than python to run programs or start ata terminal session, such as python3, your command will look like this:
$python3 -m pip install --user pygame

If the command doesn't work on macOS, try running the command again without the --user flag.

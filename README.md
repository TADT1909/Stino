# Stino

## Requirements

1. [Sublime Text](http://www.sublimetext.com)
2. [Arduino](http://arduino.cc/en/Main/Software)


## What it does

The plugin adds an Arduino dropdown menu to Sublime text from which you can access Arduino IDE features. You can create and edit sketches, verify and upload code, everything you would expect from the standard Arduino IDE, but using the Sublime text editor.

### Manage Sketches

* New Sketch - Create a new sketch in your sketchbook. This will create a sketch folder in your default Arduino sketchbook folder and initialise it with an .ino file.
* Sketchbook - Open any project in your sketchbook folder and open the sketch directory in the Sublime sidebar.

### Verify / Compile / Upload

Verify, compile or upload a sketch directly to your Arduino. You will need to have chosen a serial port to upload code to your Arduino.

### Serial port

Choose the USB port that your Arduino is plugged into. You will not be able to upload code until you have done this. You can also open the serial monitor as a file to pull debugging information out of the Arduino.

### Preferences

Change your sketchbook and build folders and set various compilation options.

## Installation
This version of Stino can be installed manually or automatic. If you installed the previous version via Package Control, please remove or disable it firstly.

Manual installation has only two steps:

1. Click menu `Preferences`->`Browse Packages...` to open the packages folder.

2. Download [zip file] from this branch, and extract the folder to the packages folder, and the Arduino menu appears.

Auto installation is much easier:
1. In Sublime Text, press hotkey Ctrl + Shitf + P
  -> Type: "Add reposistory"
  -> Enter
2. Paste this link: "https://github.com/TADT1909/Stino"
  -> Enter
3. Press hotkey Ctrl + Shitf + P
  -> Type: "Install Package"
   -> Enter
4. Type "Stino"
  -> Enter
That's it! You installed Stino.

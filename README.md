# Welcome to BlocklyDuino

BlocklyDuino is a **web-based visual programming editor for [Arduino](http://www.arduino.cc/)** electronic board.

BlocklyDuino is based on [Blockly](https://developers.google.com/blockly/), the web-based, graphical programming editor.

![](https://github.com/BlocklyDuino/BlocklyDuino-v2/blob/master/blocklyduino/media/logo_built_on.png)

BlocklyDuino provides static type language blocks and code generators for simple Arduino programming.

BlocklyDuino also supports some [Grove](http://wiki.seeedstudio.com/Grove_System/) blocks to easily get started with microcontroller-based experimentation and learning.

## Features

* Programming Arduino with visually drag and drop code blocks
* Generate fully compatible Arduino source code
* Multiple Arduino boards choice for automatic selection of pin functions
* Interact Arduino board with at least 10+ predefined Grove sensor blocks
* Load different on-site examples with url parameters
* Keyboard navigation and accessibility helpers
* Theme choice
* Block render choice
* Multi language
* Keyboard navigation

## Accessibility

You can enter _accessibility_ mode by **shift clicking anywhere on the workspace** or on a block.

Official documentation: [https://developers.google.com/blockly/guides/configure/web/keyboard-nav](https://developers.google.com/blockly/guides/configure/web/keyboard-nav)

Key mapping is customizable by activating 'open key mappings' option.

Some basic commands for moving around are below.  


### Workspace Navigation

-   W: Previous block/field/input at the same level.
-   A: Up one level (Field (or input) -> Block -> Input (or field) -> Block -> Stack -> Workspace).
-   S: Next block/field/input at the same level.
-   D: Down one level (Workspace -> Stack -> Block -> Input (or field) -> Block -> Field (or input)).
-   T: Will open the toolbox. Once in there you can moving around using the WASD keys. And insert a block by hitting Enter.
-   X: While on a connection hit X to disconnect the block after the cursor.

### Cursor 
The cursor controls how the user navigates the blocks, inputs, fields and connections on a workspace. Two different cursors:  

-   **Default Cursor**: Allow the user to go to the previous, next, in or out location.
-   **Basic Cursor**: Using the pre order traversal allows the user to go to the next and previous location.


## Demo

BlocklyDuino is a web tool. You can give it a try at
[Web](https://blocklyduino.github.io/BlocklyDuino-v2/) to see working BlocklyDuino.

## Run locally on your web browser

If you want to install it locally. Get code from github and open `index.html` in your browser.

The prefered way is to put the BlocklyDuino/web folder into a web server and open the url like localhost/index.html for use.

## Integrated Arduino upload

Soon an [Electron](https://www.electronjs.org/) version with [arduino-cli](https://github.com/arduino/arduino-cli) embbeded for an off-line version: [https://github.com/BlocklyDuino/BlocklyDuinoElectron](https://github.com/BlocklyDuino/BlocklyDuinoElectron)

## Usage

1. Open browser to BlocklyDuino and select your Arduino board, your language, your favorite theme + renderer.
2. Drag and drop blocks to make an Arduino program.
3. Select the 'Arduino' tab and copy all of the source code into an existing or new project in the Arduino IDE
4. Configure your Arduino IDE with the rght board and communication port.
5. Press the 'Upload' button in the Arduino IDE to burn the code into a connected Arduino board.

## ChangeLog

Check changelog [here](https://github.com/BlocklyDuino/BlocklyDuino/blob/master/CHANGELOG.txt)

## Tools used

[Eli Grey's File Saver](https://github.com/eligrey/FileSaver.js/)

[Google Code prettify](https://github.com/google/code-prettify)


## Authors and Contributors

Sébastien Canet ([scanet@libreduc.cc](scanet@libreduc.cc)) for this reboot and Electron version.

Fred Lin (@gasolin) for original [BlocklyDuino](https://github.com/BlocklyDuino/BlocklyDuino).

Thanks Neil Fraser, Q.Neutron from Blockly https://developers.google.com/blockly/

Thanks Arduino and Seeeduino guys for Arduino and Grove blocks.

The BlocklyDuino project is also inspired by [ardublock](https://github.com/taweili/ardublock) and [modkit](http://www.modk.it/)

This BlocklyDuino reboot project is also inspired by [Blockly@rduino](https://github.com/technologiescollege/Blockly-at-rduino),  [ardublockly](https://github.com/carlosperate/ardublockly) and [Blocklino](https://github.com/fontainejp/blocklino).


## License

Copyright (C) 2020 Sébastien Canet scanet@libreduc.cc & Fred Lin gasolin@gmail.com
-   Licensed under the GNU General Public License v3.0 (the "License").
-   You may not use this project or any file except in compliance with the License.
-   You may obtain a copy of the License at    [https://www.gnu.org/licenses/#GPL](https://www.gnu.org/licenses/#GPL).

# Blockly [![Build Status]( https://travis-ci.org/google/blockly.svg?branch=master)](https://travis-ci.org/google/blockly)


Google's Blockly is a web-based, visual programming editor.  Users can drag blocks together to build programs.  All code is free and open source.

**The project page is https://developers.google.com/blockly/**

![](https://developers.google.com/blockly/images/sample.png)

Blockly has an active [developer forum](https://groups.google.com/forum/#!forum/blockly). Please drop by and say hello. Show us your prototypes early; collectively we have a lot of experience and can offer hints which will save you time.

Help us focus our development efforts by telling us [what you are doing with Blockly](https://developers.google.com/blockly/registration). The questionnaire only takes
a few minutes and will help us better support the Blockly community.

Want to contribute? Great! First, read [our guidelines for contributors](https://developers.google.com/blockly/guides/modify/contributing).

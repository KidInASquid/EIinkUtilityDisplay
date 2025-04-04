# EinkUtilityDisplay
[Please note that this project is a work in progress and incomplete]

this project is a personal take / copy of @Ashtf 's 2025 EinkPDA, cutting a few features and adding some of my own

![IMG20250114202659](https://github.com/user-attachments/assets/c39189e0-8c66-448f-a0ef-99eec2af6684)

![IMG20250114202546](https://github.com/user-attachments/assets/446d8884-8f92-4619-9335-53f150a269c2)
credit ^ @Ashtf 

# Project Summary
  This project is a PDA powered by an ESP32-S3 running a custom "OS" written in C++ using the Arduino IDE. This project utilizes an E-Ink and OLED screen in tandem to mitigate the refresh rate restrictions of an E-Ink panel while retaining the aesthetics and benefits of using E-Ink. This project is a work in progress and currently amounts to a simple GUI for navigating between apps, a text (.txt) file editor, and a basic file manager. More applications are planned for the future and a list of TO-DOs can be found below.

  i want to improve upon the original design by changing it from a small not taking device to a smaller electronic notepad-ish form factor... i.e. the hinge folds all the way back. i'll be using a GT911 touch capacitive sensor to register inputs from a stylus. it will still have the same keyboar but i also want to include dedicated Ctrl+Z, and Ctrl+Y shoulder buttons to help with the 'drawing' features. i dont expect to 


# TO-DO
- Tasks app
- Scrolling w/ OLED preview
- Transfer to/from PC via BT/USB
- use SD card for stroage
- add reading light
- fix e-ink refresh on every button press
- Battery icon for charging
- crystal/ coin battery for internal time keeping
- scroll wheel/buttons
- Refresh() and refreshPartial() using new display() knowledge
- Add cooldown on partial and full refresh, look up times
- Add safeguards, counter on partial that forces full update
- Debug refresh happening on each button press, use serial monitor
- LED indicators on the outside (battery low, sleep mode, etc.)
- Calendar app *very low priority


# License
All files are distrubuted under GNU GPLv3 license:

EInkPDA - A small note-taking and productivity device using E-Ink and OLED.

Copyright (C) 2025 Ashtf

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.


This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.


You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

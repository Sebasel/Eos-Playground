# Eos-Playground
Updated version of Amy Worall's [eos playground](https://github.com/amyworrall/eos-playground) to work with 1.62.0

### note:
Tested and working on teensy 3.x boards.

compared to the original there are some changes around `yield.cpp` and an additional edit in teensyduino's boardstack regarding `print.cpp`
I highly recommend watching [their video on](https://youtu.be/2jeyQjmPyMM) the process to understand what is happening behind the scenes.

## Installation:

  ### MacOS:
  1. Replace `boards.txt` in `~/Library/Arduino15/packages/teensy/hardware/avr/1.62.0/` with the provided file
  2. Replace `usb_desc.cpp`, `usb_desc.h`, `yield.cpp` and `print.cpp` in `~/Library/Arduino15/packages/teensy/hardware/avr/1.62.0/cores/teensy3` with the provided files

  ## Windows:
  1. Replace `boards.txt` in `%appdata%\<UserName>\local\Arduino15\packages\teensy\hardware\avr\1.62.0` with the provided file
  2. Replace `usb_desc.cpp`, `usb_desc.h`, `yield.cpp` and `print.cpp` in `%appdata%\<UserName>\local\Arduino15\packages\teensy\hardware\avr\1.62.0\cores\teensy3` with the provided files

  

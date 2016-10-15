# telepresence-robot
Arduino Jhonny Five project

### Next steps
- I'm not sure if servo controller example is correct in terms of max velocity, and params. Check that.
- Make Step motor to work.


### Running

sudo apt-get update && sudo apt-get install arduino arduino-core 

1. Run `npm install` to install server dependencies.

2. Run the following lines (linux only):
    - `$ sudo usermod -a -G dialout <username>`
    - `$ sudo chmod a+rw /dev/ttyACM0`



### Troubleshooting

https://github.com/rwaldron/johnny-five/wiki/Getting-Started#trouble-shooting

If the above didn't work as expected, make sure that StandardFirmata is installed on the board:

    - Download Arduino IDE
    - Plug in your Arduino or Arduino compatible microcontroller via USB
    - Open the Arduino IDE, select: File > Examples > Firmata > StandardFirmata
    - Click the "Upload" button.
    - If the upload was successful, the board is now prepared and you can close the Arduino IDE.


"Changing the baud rate (to 57600) in the Firmata sketch solved the problem."

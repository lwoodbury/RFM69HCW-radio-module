# RFM69HCW Radio Module

Simple send and receive examples for Adafruit's RFM69HCW Radio module with Arduino Micro and Teensy 

Prepare radio as described here: https://learn.adafruit.com/adafruit-rfm69hcw-and-rfm96-rfm95-rfm98-lora-packet-padio-breakouts

Circuit examples also included as Fritzing (fzz) files and png image
This is an SPI serial communication device so you need to connect to the Teensy/Arduino's SPI pins (check the Teensy pinout diagram!) and the others described in the code

Teensy version of Radiohead library: https://github.com/PaulStoffregen/RadioHead

The only change made to the given examples was to initialise the HCW radio by adding a 'true' argument to the following line:

rf69.setTxPower(20, true);  // range from 14-20 for power, 2nd arg must be true for 69HCW





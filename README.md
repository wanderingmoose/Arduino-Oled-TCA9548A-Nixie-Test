# Arduino with Sideways 5 oleds using a TCA9548A multiplexer
This sketch is used for testing bitmaps numbers on 5 Oleds displays.
This is the precursor to creating a Nixie style display. 
-- Added files under code for AHT10 temperature sensor and a simple clock using a DS1307 RTC.
![20240709_202533](https://github.com/wanderingmoose/Arduino-Oled-TCA9548A-Nixie-Test/assets/12417916/8b09ebd7-ef6e-4196-a0da-c6270716841a)
Like all my other repositories, I put my info here for my future knownledge. If any of this helps you, cool.
It took me a long time get the leading zeros not to be displayed.  But Dam!!! I got it figured.

# Clock
## My favorite sketch is oled_TCA9548A_SWs_numbers_5_Clock_Works.ino.
Under code directory there are afew sketches for a clock. These sketches are the same code for sideways Oled 128x64 pixel displays, but with different bitmaps for the numbers. Fonts used are Nixieone and 7 Segement. Also ones for 128x32 Oled displays.
Wiring:
TCA9548A has 8 I2C channels. Which allows for up to 8 displays. 
Display 5 is on channel 0 and display 1 is on channel 4. (Display order-5,4,3,2,1) Display 1 is the least signifigant digit. 

I just have a simple analog input to test the display and show values.

# Pictures

![20240709_202603](https://github.com/wanderingmoose/Arduino-Oled-TCA9548A-Nixie-Test/assets/12417916/54686d54-8c55-45ee-a0c5-67162555fb5e)
![20240709_202519](https://github.com/wanderingmoose/Arduino-Oled-TCA9548A-Nixie-Test/assets/12417916/c122fbe5-5ec6-4458-9429-13f592fe40bb)
![20240709_202515](https://github.com/wanderingmoose/Arduino-Oled-TCA9548A-Nixie-Test/assets/12417916/6f25642d-5330-4bca-9372-00fcdc457f96)


# Arduino with Sideways 5 oleds using a TCA9548A multiplexer
## (Updated and added in code with buttons to adjust time, also still has the AHT10 sensor.July 28, 2024 Version 4)
This sketch is used for testing bitmaps numbers on 5 Oleds displays.
This is the precursor to creating a Nixie style display. 
-- Added files under code for AHT10 temperature sensor and a simple clock using a DS1307 RTC.
### Clock using my favorite sketch that can be found under code. oled_TCA9548A_SWs_numbers_5_Clock_Works or better Olded_V3_OLED_SW_Clock_AHT10_Works
![20240721_134510](https://github.com/user-attachments/assets/498c8c79-8433-4537-840d-a20d9c812102)
![20240722_184140](https://github.com/user-attachments/assets/ddcfdf51-8ca6-4643-a17a-8785e928954f)

### The old bitmaps, they were smaller then what I am using now. Analog input on this one.
![20240709_202533](https://github.com/wanderingmoose/Arduino-Oled-TCA9548A-Nixie-Test/assets/12417916/8b09ebd7-ef6e-4196-a0da-c6270716841a)
Like all my other repositories, I put my info here for my future knownledge. If any of this helps you, cool.
It took me a long time get the leading zeros not to be displayed.  But Dam!!! I got it figured.
# Clock
## My favorite sketch is oled_TCA9548A_SWs_numbers_5_Clock_Works.ino.
## Update Olded_V4_OLED_SW_Clock_AHT10_BUT_Works is now my favorite code.
## Now my favorite sketch is Olded_V3_OLED_SW_Clock_AHT10_Works. Enjoy. :)
Under code directory there are afew sketches for a clock. These sketches are the same code for sideways Oled 128x64 pixel displays, but with different bitmaps for the numbers. Fonts used are Nixieone and 7 Segement. Also ones for 128x32 Oled displays.
Wiring:
TCA9548A has 8 I2C channels. Which allows for up to 8 displays. 
Display 5 is on channel 0 and display 1 is on channel 4. (Display order-5,4,3,2,1) Display 1 is the least signifigant digit. 
# Laser Cut Oled display holder, 5 Diplays 128x64 0.96".
### There are two types of holders, one that just holds the displays.
### The other holds the displays and just shows the working area.
### These are found under docs.
# Pictures

![20240709_202603](https://github.com/wanderingmoose/Arduino-Oled-TCA9548A-Nixie-Test/assets/12417916/54686d54-8c55-45ee-a0c5-67162555fb5e)
![20240709_202519](https://github.com/wanderingmoose/Arduino-Oled-TCA9548A-Nixie-Test/assets/12417916/c122fbe5-5ec6-4458-9429-13f592fe40bb)
![20240709_202515](https://github.com/wanderingmoose/Arduino-Oled-TCA9548A-Nixie-Test/assets/12417916/6f25642d-5330-4bca-9372-00fcdc457f96)

#### Fixie Nixie Olde Display 

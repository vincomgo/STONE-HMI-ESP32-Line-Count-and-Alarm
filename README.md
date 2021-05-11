# STONE-HMI-ESP32-Line-Count-and-Alarm
STONE HMI ESP32 Line Count and Alarm

Project Overview
 

Here we do the production line counting application, after boot, stone TFT The LCD serial port screen will have a start interface. After a short stay, it will jump to the specified page 1 and display the time setting. At this time, it is necessary to set the current time. Another option is to have a record of the number of fires, which will be added one each time, which can be used as the basis for fire control on the production line. After the time setting is completed, it will be displayed on the next interface, and click OK Enter the set production target as the assessment basis. After setting, click OK to enter the counting interface. Here, the data uploaded to esp32 through the sensor, and then transmitted to the stone TFT LCD serial port screen through esp32. One will be added each time. The current output rate will be calculated according to the target quantity, and the data will be updated every time an object is detected.

 

The communication functions are as follows:

 

① The serial port screen of stone TFT LCD realizes the function of button switching interface;

② The serial port screen of stone TFT LCD realizes the function of an automatic jump when starting up;

③ The serial port screen of stone TFT LCD realizes time setting;

④ The serial port screen of stone TFT LCD realizes data variable distribution;

⑤ Stone TFT LCD serial port screen realizes serial command communication.

 

Modules required for the project:

 

① STONE TFT LCD；

② Arduino ESP32；

③ Infrared detection module;

④ Smoke detection module.

Click here for the full article: https://www.stoneitech.com/application/machinery/stone-hmi-esp32-line-count-and-alarm.html

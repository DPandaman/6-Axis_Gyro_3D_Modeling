# 6-Axis Serial Modeling
Basic 3-D Modeling Simulation for 6-Axis Gyroscopes and Accelerometers.

This code serves as only the visualizer for Pitch, Roll, Yaw (PRY) values. You must have an *additional* script that handles calculating and logging the values. 

Requirements:
   + A 6-Axis Accelerometer/Gyroscope (UART, SPI, I2C, Wireless, etc.)
   + A Serial USB connection between your Accelerometer and PC
   + A Chromium-based browser (Chrome, Edge, Opera) to open this file. Safari, Firebox, and others are not supported

***Due to the many acclerometers and programming options available, make sure your serial messages are in this general format!***
```
serial.log("PRY:");
serial.log(pitch);
serial.log(",");
serial.log(roll);
serial.log(",");
serial.log(yaw\n);
```
> (Example Serial print) PRY:-34.2,12.4,-76.9 (make sure no spaces and new lines for each entry)


Check out more details for instructions and modifications [here](https://dpandaman.github.io/projects/6-axis_gryo_visualizer.html)


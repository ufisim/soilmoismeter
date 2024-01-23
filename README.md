# Soil Mois Meter

Soilmois a multifunctional and convenient soil moisture measuring device for the standard user.
Look for more information in the Wiki section. There you can find articles on how the device works, how to switch it on, how to build a similar device.
https://github.com/ufisim/soilmoismeter/wiki

| Module | Library / Driver | Function | Value |
| :---         | :---      | :--- | :---  |
| "UNO" Board   | CH340G     | System management    | Manage all ports, pins, system.    |
| QAPASS 1602 Display    | Liquid.Crystal I2C       | Information output      | Display the interface, text and other types of information on the screen in graphical form.     |
| RGB LED    | No       | Displaying the device status      | Display of several device operation modes: red - device setting; green - device operation; flashing blue - device switched on;      |
| Light Sensor    | No       | Determination of illuminance      | Signal to cancel the buzzer sound, in case of low soil humidity, if the room is dark.      |
| Buzzer    | No       | Beep      | It beeps when the soil moisture is too low.      |
| Soil moisture sensor    | No       | Measuring soil moisture      | The main module in the device. Measures soil moisture.      |
| Button    | No       | Signal when pressed      | When pressed, sends a signal about it to the board. Used to control      |
| Battery    | No       | Power      |       |

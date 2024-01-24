# Soilmeter: Don't forget to water.
![image](https://github.com/ufisim/soilmoismeter/assets/143403528/426ddba6-ede4-44ac-8e0d-029a27529055)

Soilmeter is a handy device for measuring soil moisture that has a number of useful functions, making the process of plant care more efficient. Here are some of its benefits:

- Measurement accuracy: The Soilmeter provides accurate soil moisture measurements, which helps maintain optimal moisture levels for plants.

- Customisation: The device is easy to set up, making it suitable for use in a variety of conditions.

- Low Moisture Reporting: The Soilmeter is able to report low soil moisture, helping to provide timely alerts when watering is needed.

- Time since last watering: It also displays the time since the last watering to help you maintain an optimal irrigation regime for your plants.

- Portability: The Soilmeter has a lightweight and portable design, making it convenient for use indoors and outdoors.

- Won't disturb: the device won't beep when the room is dark.

- Overall, the Soilmeter is a handy and functional device that helps to maintain optimum moisture levels and conditions for plants.


![Снимок экрана 2024-01-24 215719-PhotoRoom png-PhotoRoom](https://github.com/ufisim/soilmoismeter/assets/143403528/ebfba804-3b8f-42c0-872d-f1ea133b67e6)




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

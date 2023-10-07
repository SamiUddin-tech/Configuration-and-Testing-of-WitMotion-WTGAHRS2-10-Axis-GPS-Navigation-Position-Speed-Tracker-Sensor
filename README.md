# Configuration-and-Testing-of-WitMotion-WTGAHRS2-10-Axis-GPS-Navigation-Position-Speed-Tracker-Sensor

![ezgif com-webp-to-png](https://github.com/SamiUddin-tech/Configuration-and-Testing-of-WitMotion-WTGAHRS2-10-Axis-GPS-Navigation-Position-Speed-Tracker-Sensor/assets/81253183/f9f41270-4134-487e-9351-f6df0cc01430)

In this project, I configured the [WitMotion WTGAHRS2 10 Axis GPS Navigation Position Speed Tracker Sensor Accelerometer + Gyro + Angle + Magnetometer + Barometer](https://www.wit-motion.com/inertial-navigation/witmotion-wtgahrs2-10-axis-gps.html): -

## Step 1. Setting up WIT Motion Sensors and Software (Windows 10)
1. First Download the files of WIT motion via this link.
2. Install Serial Communication Drivers
3. Connect the WIT Motion sensor device to your computer using the provided USB cable. The USB cable, which consists of four wires: Red, Black, Yellow, and Green.
Connect the wires as follows:
PICTURE
Red wire to 5V power.
Black wire to ground (GND).
Yellow wire to RX (receive) on the USB connector.
Green wire to TX (transmit) on the USB connector
4. Install the required serial communication drivers if they are not already installed. You can find these drivers in the downloaded files.

## Step 2: Launch the WIT Application
Locate and launch the WIT Application on your computer.

## Step 3: Configure the WIT Application
In the WIT Application, you'll find a left sidebar with options.
Under the "Modular Category" section, select "HWT905-TTL" to specify the type of sensor.
Next, connect your sensor to the GPS module. In the same left sidebar, find the "COM Port" option and select the appropriate COM port for your GPS module. 

![image](https://github.com/SamiUddin-tech/Configuration-and-Testing-of-WitMotion-WTGAHRS2-10-Axis-GPS-Navigation-Position-Speed-Tracker-Sensor/assets/81253183/21ab3ff7-bd39-46a9-823d-cab132f01894)

## Step 4: Configure Data Output
At the top-right corner of the WIT Application, click on "Config."
In the configuration settings, specify the desired data output you need from the sensor.

## Step 5: Retrieve GPS Information
To obtain GPS information, follow these steps: 

![image](https://github.com/SamiUddin-tech/Configuration-and-Testing-of-WitMotion-WTGAHRS2-10-Axis-GPS-Navigation-Position-Speed-Tracker-Sensor/assets/81253183/2ab64855-0ea8-4f32-b68a-a00ce9eac73e)

1. Click on "GPS Original" in the WIT Application.
2. Then, click on "Read Config."
3. Deselect "GPS Position."
4. Check the boxes for "Position Accuracy," "PDOP," "Location," and "Port."
5. Finally, click "Read Config" again to save these settings.

## Step6: Data Collection

With your sensor connected and configured, the WIT Motion sensors will now collect and provide the specified data as per your configuration.
This setup guide should help you get started with the WIT Motion sensors and software. Make sure to refer to the official documentation for any additional information or troubleshooting.
Then click on the Data you will have all the data outputs including latitude, longitude and no of satellites.

![image](https://github.com/SamiUddin-tech/Configuration-and-Testing-of-WitMotion-WTGAHRS2-10-Axis-GPS-Navigation-Position-Speed-Tracker-Sensor/assets/81253183/191e613d-dfb0-40df-8d0c-52fab9091ddd)


# Using WIT Motion Sensors with Python


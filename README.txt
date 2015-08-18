INSTALLATION

1. If this is the first time running the application on the computer or the device was previously paired with another computer, you must pair the device through bluetooth first. 
	The device name is "HC-06", but may appear as "Unknown" initially. The device
		password is "1234".
	Note: If the device was previously synced to another computer, you must first 
		remove the device from that computer before pairing it with the current one.

2. Start the application, located in the respective folder in the MPU3D folder. Select the bluetooth port to use. 
	On Windows, this is usually "COM3" or "COM6" for bluetooth and “COM1” for USB.
	On Mac, this is usually "/dev/cu.HC-06-DevB" for bluetooth and “/dev/cu.HC-06-DevB” for USB.

3. Position the Arduino to face away from the monitor, to the left, for optimal tracking. The Arduino should point to the 9 o'clock.
	(The front of the Arduino is defined as the side with the two LEDs on it.)

TROUBLESHOOTING

1. If the Arduino stops responding for any reason, use one of the following methods:
	a. Reset the Arduino. The button is near the battery connection.
	b. Restart the tracking app.
	c. Unplug the Arduino, then plug it back in.

2. If no model appears in the window, make sure you have the .stl model file in the same directory as the executable.

SOURCE CODE

1. The Arduino source code is located in the MPU6050_DMP6 folder. You will need to download the Arduino software here: https://www.arduino.cc/en/Main/Software.
	Note: If you need to upload code to the device, make sure to do it over usb. Connect the Arduino to the computer, and then select Tools -> Port and the correct usb port. (Use trial and error to find the correct port)
	
2. The Processing source code is located in the MPU3D folder. You will need Processing software to open and edit the code, found here: https://processing.org/download/.
	To compile the code as an executable, select File -> Export Application

For any other questions, please contact the owner on github.
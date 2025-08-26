# Modbus-Monitor-Green
The Modbus Monitor Green Studio is a kinda   
Modbus/RS485 data scquisition software over ethernet, wifi, serial port, bluetooth   
Auto Terminal Language ATeL   
Alias is Modbus Terminal, Auto Terminal, SCADA   

Allows:
1.	High-Level supervision of machines and hardware with programmable logic.
2.	Automate data asquision process with hardware over Ethernet/WiFi, Bluetooth, Serial Port.
3.	It may be or may part of distributed control system (DCS) that control sensors, devices.
4.	Operator interface which enable monitoring and the issuing of process commands.
5.	Real-time programmable control logic and controller calculations
6.	Ability to perform supervisory operations over a variety of proprietary devices.
7.	Visually present data acquisition flow with possibilities of customization the data i/o operations.
8.	Keep all the data for further analysis.
9.	Build graphic of the gotten or calculated data and show that graphic for user.
10.	Keep history of measurements and data as sessions.

The story

Initially the program was developed for communicating with Modbus and OBD II proprietary hardware. Eventually it became   
SCADA like system with possibility of running programmable logic for controling different hardware and make data measurement graphics.

In particular, towards to Modbus families protocol the application allows:

1.	Read Modbus (rs-485) device's data and save it in file.
2.	Customize the input data stream with additional keys, values. Create the required data structure on the fly and redirect it as a stream to a file.
3.	Write modbus data to rs-485 device.
4.	Configure a modbus device with appropriate parameters (bit rate, data bits, stop bits, parity flow control, port interval timeouts) and user notes for convince.
5.	Configure a session with COM port, existing device configuration and bind scenario. 
6.	Develop user modbus data scenario for data communication with hardware.
7.	Running user's scenario with selected device within configured session. App displays output of the scenario showing user the execution progress, intermedia data & other.
8.	Display graphics with session modbus data.
9.	Setting up system settings for enriching io possibilities and adapting it for hosting hardware.

More details you can find in other specific topics.

Tested with the following devices:
1. ESP8266, ESP-01S: WiFi switch
2. ELM327 OBDII USB scanner
3. ELM327 OBD II Bluetooth scanner
4. ELM327 OBD II WIFI scanner
5. PZEM-004, PZEM-017 Voltmetter Current Meter, Energy Meter
6. USB-TTL CP2102 USB to TTL UART module
7. USB-TTL PL2303 USB to TTL UART module
8. TTL To RS485 Module Hardware Automatic Flow Control Module Serial UART Level Mutual Conversion Power Supply Module 3.3V 5V   
...Many others

![Device Properties](/app-device.png?raw=true "Device Properties")



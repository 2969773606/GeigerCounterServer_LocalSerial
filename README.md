# GeigerCounterServer_LocalSerial
GeigerCounterServer Local Serial communication
The Geiger counter calculates the radiation intensity and sends the data through the serial port, and the upper computer (PC or Raspberry Pi) runs the python program to read the serial port data and draw it in the graph. Communication through the computer's USB port. This solution can be used when the number of nuclear radiation sensors (Geiger counters) is small, such as 1 to 5, and the data processing requirements could be also relatively simple. When the number of sensors is relatively large, you can consider using the form of 485 bus (using Modbus-RTU protocol). This Modbus-RTU communication will be described in another article.

Material list:
1) Geiger counter (with Arduino nano)
2) Computer (or Raspberry Pi)


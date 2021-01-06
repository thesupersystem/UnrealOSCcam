# UnrealOSCCam

UnrealOSCCam allows the user to connect to the OSC receiving device using an ESP32 microcontroller. Commands are sent via OSC Message.
Cameara setup includes 2 joysticks, 2 potentiometers and 2 buttons.

06/01/21

1.0

How to use :

Power up micocontroller by plugging in the power to the usb port.IP Address can be checked by uploading code into microcontroller again. IP Address will be printed in the serial monitor.Next, access the webpage to key in OSC listener's IP Address and port number. This will be the computer running Unreal Engine. Below are the callouts for the components :

Joystick 1 = /joy1 (2 inputs)
Joystick 2 = /joy2 (2 inputs)
Potentiometer 1 = /pot1 (1 input)
Potentiometer 2 = /pot2 (1 input)
Button 1 = /sw1 (1 input)
Button 2 = /sw2 (1 input)


Wifi password and router name are hard-coded. A captive portal will be used in the next version.


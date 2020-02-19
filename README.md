# Manet-based-Chat-System-Relay-and-DC-Motor-Speed-Control using Raspberry Pi
This project is visioned to provide a backup radio tower when all fails during any natural disaster where it can be used to communicate with people remotely using this network. Also can control various types of electrical devices by triggering them by ON and OFF and Also can control the Speed of 12V DC Motor using L239D Motor Driver we can control upto 2 DC motors and their speed.

They can be controlled via the Chat System by sending a particular keyword to activate the device.

Keywords:

light on, light off => to control the electrical device by using a 5V Relay.

start motor, stop motor => To enable and disable the PWM devices at 0 Speed.

1off,2off,0off => Switch the motors back to 0 Speed.

f1low,f1mid,f1max => Motor 1 on forward at various speed.

r1low,r1mid,r1max => Motor 1 on reverse at varoius speed.

f2low,f2mid,f2max => Motor 2 on forward at various speed.

r2low,r2mid,r2max => Motor 2 on reverse at varoius speed.

f0low,f0mid,f0max => Motor 1,2 on forward at various speed.

r0low,r0mid,r0max => Motor 1,2 on reverse at varoius speed.


Lets get Started.

Step 1: Enable your SSH Mode in you Raspberry Pi.

Step 2: Now Enable Ad-Hoc mode in your Pi. Refer MANET Ad-Hoc

Step 3 : Setup a DHCP Server to auto assign IP for the Connecting Devices. Refer MANET DHCP

Step 4 : Reboot the Pi to Finalize all the Settings.

Step 5 : Now Execute the TCP Host PWM program in the Pi.

Step 6 : Now Execute the TCP Client program in the Mobile. Important : Ad-Hoc Mode supports only on Apple Devices.

That's it.

ISO File: https://drive.google.com/drive/folders/1eBFIkIY1_ZnR4nsH-xFMVjZkt3R2M9e2?usp=sharing

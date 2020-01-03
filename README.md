# Bluetooth_car_l298
Wireless Bluetooth controlled robot.

Bluetooth controlled wireless robot V2.0
#######################################################################
4 motors are being controlled using an l298n motor driver module. Motors of the same side are connected to each other to save pins since they will be working in the same direction anyways.
Looking at the data sheet of l298n I found that max current it can handle is 1 Amp (according to the data sheet) but I wouldn’t trust it with anything above 0.8ma (trust me I have burnt my fare share if ICs). So, if you are using a heavy motor (I used 500 rpm Johnson Motors) that demand higher currents I’d suggest to use a driver shield over your Arduino with high current ratings (or use 2 motor drivers like me, one for each side of motors) .
App that you’ll need - Arduino Bluetooth RC Car
#################################################################
Link for the app
https://play.google.com/store/apps/details?id=braulio.calle.bluetoothRCcontroller&hl=en_IN

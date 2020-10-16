# Eryone2560-
Eryone2560 Marlin 2.0.7 ThinkerS V2

This is my taken on Marlin 2.0.7 as the firmware provided by Eryone was a older Marlin 2.0.x bugfix version. 
I have included a edited pins_RAMBO.h file if you want to try your own hands on configuring vanilla Marlin as Eryone pins location is slightly different. 
You can find that .h file in Marlin > src > pins > rambo

Attention:
This firmware is for Eryone 2560 main board. It is an 8bit Atmega2560 processor. 
This is for stock printer, No BL Touch or probe. Some of the function are listed below:

1. BedtempPID is enabled. 
2. S Curve acceleration
3. Mesh Bed Leveling 5x5 Grid
4. Mesh steps set to 0.04mm increments. 
5. Level Bed Corners 
6. Baby stepping set to 0.02mm 
7. Loading/Unloading filaments

Please do your own basic calibration needed.
1. Nozzle PID (/Bed PID)
2. estep
3. Acceleration 
4. Junction Deviation 
5. Mesh bed 
6. tc


ThinkerS Marlin2.0.7 Doc.rtf is a documentation of what I have changed in Marlin. 

Note: 
So far this firmware config works for me, but I will not responsible for how it behaves on your printer. 
Please know what you are doing. 

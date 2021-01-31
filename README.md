# Release
Contains released UI

MotorController 1.3.31:
- Save parameters to file missing get of last parameters 
- Load paramteres from file bug fix

MotorController 1.3.30:
- Plot internal error after FW update
- Bode plot background color changed depending of released version (STXI/REDLER) 

MotorController 1.3.29:
- Save parameters to file - checksum verification operation changed
- Databases enable/disable specific command added
- Database tooltip->protocol information added
- CAN: Can button, window, class added - ready for operation implementation
- Rx Event function changed to "DataReceived"
- description of packets -> shorten routes
- Tx event replaced by static function
- Some code useless deleted

MotorController 1.3.28:
- Save data to .csv file - data values comma separator for float number, replaced by dot
- Frequency calculation bug fix
- Connect process improved
- Bode window error loading twice bug fix
- New calibration command added
- New Feedbacks Status added
- New Feedback sync command added
- Speed profiler -> profiler mode changed to enum
- Baudrates 1875000 & 1250000 added to "forceConnect" mode (debug tab)
- Frame Color integration verified

MotorController 1.3.27:
- improve select plot from channel combobox
- Rx/Tx message string indicator, bytes swapped
- ECHO from driver when "set" operation is sent from "Debug" tab
- Plot frequency bug fixed
- Plot scale bug fixed
- Frame color for error log added
- Hexadecimal values can be set via "Debug" tab
- Reading FW version removed from serial programmer procedure
- Progress bar increase process updated during serial programmer procedure
- Compatibility with Baudrate 19200
- Speed error commands added in "Motion" tab

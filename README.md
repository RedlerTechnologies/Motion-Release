Please note - From version 1.3.38a (not included), we add all the release files in the "Releases" section inside the repo.

# Release
Contains released UI

MotorController 1.3.37a:
- Communication statistics window added.  
- Monitor (sniffer) mode added.
- Advanced mode added.
- Kd option added to all sections in PID tab.
- Filter section moved to device tab.
- More Input/Output added.
- Command summary table added to debug tab.
- Log file added to "Documents/MotorController/Logs/".
- Show log button added for resizing the log window.
- More calibration configurations added. 


MotorController 1.3.34a:
- Read system "NumberGroupSeparator" and show it in "Delimiter" control  
- CAN Open objects window added
- ToggleSwitch unchecked background color changed
- Parameters window resize is now enable
- Connect time process improved
- Graph -> Plot up to 8 channels simultaneously
- Graph -> "Reset": Reset channels Scale/Offset made by mouse action when the "Freeze" option is activate
- Graph -> "Load": Read from configuration file the user parameters for each channel, send to driver the "Source" and "Priority"
- Graph -> "Save": Save to configuration file all channels parameters
- Each plot channel has it owns color and can be changed by clicking the colored box
- Each plot channel has it owns Priority, Scale, and Offset
- Each plot channel can be autoscaled (calculate Scale and Offset) by clicking "Fit to size" icon near the colored box

MotorController 1.3.33c:
- Excel delimiter option added via a ‘ComboBox’ in main panel (near “record” button)

MotorController 1.3.33b:
- Excel delimiter changed (Take in consideration STX version, using ';' instead of ',')
- BP interfaces improve (Signal generator group ->  Margin added)

MotorController 1.3.33:
- New operation added (Parameters -> Motion -> Stop Motion - > Enable Gate Driver)
- Operation ID, Index wrong fixed (BP -> Reports -> Position Counters -> Main)
- Read only parameters limitation (db integration was missing)
- BP interfaces improve (blank space added)

MotorController 1.3.32:
- Calibration timeout occurred when running via wizard window

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

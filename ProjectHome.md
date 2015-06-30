Binding for Ruby on Windows to read Inter Sense gycompasses

This binding is simple:
  * Only supports 3-DOF devices, returns yaw, pitch, roll angles
  * Only supports one tracker at a time, typically connected to the computer through serial-USB converter.

## API ##

Class WinterSense:
  * open
  * close
  * angles
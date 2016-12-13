# GPS-Navigation-MSI

Publisher node:
Connect USB of APM to Laptop
run : rosrun mavros mavros_node _fcu_url:=/dev/ttyACM0:115200

Subscriber node : 
Mavros package for extracting data from Ardu pilot MEGA (GPS module Ublox Neo 7m with compass)
Data received at 2 readings per second
Calculating navigation angle based on direct (long,lat) coordinates
Calculating distance between current and target on the great circle

Yet to update:
packages.xml
CmakeLists.txt

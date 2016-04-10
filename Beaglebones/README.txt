Explanation :
Captor send message from 433MHZ wave. 
An RFXCOM antenna get this message.
RFXCOM is connected to beaglebone by USB port.

Beaglebones: 
Install mosquitto and mosquitto-client
Launch the python script and all message be catch and thrown to an public broker.

rfxcom -> /opt/rfxcom

running script :
1) cd opt/rfxcom
2) ./rfxcmd.py -d /dev/ttyUSB0 -l -v



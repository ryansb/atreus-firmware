LAYOUT=norman make jsonlayout
make
sleep 2
sudo avrdude -p atmega32u4 -c avr109 -U flash:w:atreus.hex -P /dev/ttyACM0

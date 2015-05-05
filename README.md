# py_sensortag

Base on this repo https://github.com/msaunby/ble-sensor-pi

Strip all sensors but keeps acc sensor

And allow to change advertise period by change this code in sensortag.py

`py
tag.char_write_cmd(0x34,0xAA) 
`

now the period is aboout 100ms

change 0xAA to 0xFF will make the period to 150ms

change to 0x01 will make the period to 1000ms

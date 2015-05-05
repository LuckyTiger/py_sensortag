# py_sensortag

Base on this repo https://github.com/msaunby/ble-sensor-pi

but strip all sensors but acc sensor

and allow to change advertise period by change this code in sensortag.py

`py
tag.char_write_cmd(0x34,0xAA) 
`
change 0xAA to 0xFF will make the period shorter


# GL-3 (Mechanical scanning 2D LiDAR)

## Guide
- Installation
Install dependencies
```
$ pip3 install -r requirements.txt
```
and download 'gl_python_driver' from git
```
$ cd ${Workspace}
$ git clone https://github.com/soslab-project/gl_python_driver.git
```
- Set permission of USB port
```
$ sudo chmod a+rw /dev/ttyUSB0
```
- Set permission of USB port permanently
```
$ sudo usermod -a -G dialout $USER
```
and reboot.
- Run GL-3 python scripts
```
$ python3 gl_python_driver.py
```

## Test environment
- Ubuntu 18.04
- x86_64 (PC)

## Application demo
- [GL-3, Demo] 2D LiDAR, Mapping (https://youtu.be/AfsqlU_f-Go)
- [GL-3, Demo] Create 3D Point Cloud with 2D LiDAR (https://youtu.be/_HBWe95GqXM)
- [GL-3, Demo] Create 3D Point Cloud with 2D LiDAR (pulse-width version) (https://youtu.be/q4MeeS9eP4c)
- [GL-3, Demo] Human Tracking Demo of Multiple Mobile Robots (https://youtu.be/ZzEvm8gMPaA)
- [GL-3, Demo] 2D LiDAR Object Detection (https://youtu.be/V29QzU9AcQo)

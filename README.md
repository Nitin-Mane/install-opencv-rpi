# install-opencv-rpi
Install Opencv in raspberry pi 3 &amp; 4 hardware. 


Install the dependencies 

```
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install cmake gfortran
$ sudo apt-get install python3-dev python3-numpy
$ sudo apt-get install libjpeg-dev libtiff-dev libgif-dev
$ sudo apt-get install libgstreamer1.0-dev gstreamer1.0-gtk3
$ sudo apt-get install libgstreamer-plugins-base1.0-dev gstreamer1.0-gl
$ sudo apt-get install libavcodec-dev libavformat-dev libswscale-dev
$ sudo apt-get install libgtk2.0-dev libcanberra-gtk*
$ sudo apt-get install libxvidcore-dev libx264-dev libgtk-3-dev
$ sudo apt-get install libtbb2 libtbb-dev libdc1394-22-dev libv4l-dev
$ sudo apt-get install libopenblas-dev libatlas-base-dev libblas-dev
$ sudo apt-get install libjasper-dev liblapack-dev libhdf5-dev
$ sudo apt-get install protobuf-compiler
# The latest Debian 11, Bullseye don't support python2 full
# don't try to install if you're having a Raspberry Bullseye OS
$ sudo apt-get install python-dev python-numpy
```

Install OpenCV-4-5-5

# check your memory first
```
$ free -m
```

download the file 
```
$ wget https://github.com/Nitin-Mane/install-opencv-rpi/OpenCV-4-5-5.sh
```

set config file 
```
sudo chmod 755 ./OpenCV-4-5-5.sh
```

Install the process 
```
./OpenCV-4-5-5.sh
```

# Automatic-wiper-on-car

Need Toor
nVidia Jetson nano 2GB, tp-link Archer T2UPlus, logiccol C270n HD WEBCAM, Tower Pro SG90

This machine learns the water droplets on the glass. And it can automatically wipe the water droplets on the glass.

This use model RESNET18
Classification
2 categories - ‘NOT’ or ‘WIPE’


You can use a CSI camera but I tested with a USB camera so you will have to make code modifications on your own.

1. install smbus
   
   apt install python-smbus

2. install FaBoPWM
   
   git clone https://github.com/FaBoPlatform/FaBoPWM-PCA9685-Python
   pip3 install .
   pip3 install smbus

3. follow wiper0-Copy1.ipynb 



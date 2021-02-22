# ROSandNovintFalcon-Interface
# Description
-Interfacing the Novint Falcon + ROS using libnifalcon:

"libnifalcon is a library that helps to interface ROS(<kinetic> version & others like melodic etc...) with Linux Ubuntu 16.04"

● Required other supporting libraries:
1. cmake
   http://www.cmake.org/
2. libusb 1.0 (Recommended for Linux or Mac)
   http://www.libusb.info
3. GLUT 
4. libasound2
5. ftd2xx (Recommended for Windows)
   http://www.ftdichip.com/Drivers/D2XX.htm

➢ "libnifalcon installation steps"
1. clone the libnifalcon library at home folder.
   $ git clone https://github.com/libnifalcon/libnifalcon.git
   $ cd libnifalcon
   $ mkdir build
   $ cd build/
   
2. cmake it in build using the command below :
   $ cmake -G "Unix Makefiles" ..
   $ make
   $ make install
   (hint- if you get some error in make install,then use the command)
   $ sudo make install

➢ Run the following examples and test the Novint Falcon functionality:
   $ sudo falcon_led
   $ sudo findfalcons

.......THESE STEPS MAKE SURE THAT LIBNIFALCON IS INSTALLED SUCCESSFULLY........

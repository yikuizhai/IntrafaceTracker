# Intraface Tracker

## Overview
Face tracker demo based on [IntraFace](http://humansensing.cs.cmu.edu/intraface/index.php)(version 1.2). The program would track the biggest face in the camera view and the face landmarks would be drawn on the face.

## Announcement
You should get the dependency(header files, models, libs etc.) from [IntraFace](http://humansensing.cs.cmu.edu/intraface/index.php) that this project doesn't provide.

## Usage  

For **windows users**:

* Download this project
* Put IntraFace header files into `win32\include\intraface` 
* Put `IntraFaceDLL.lib` into `win32\lib\Debug` and `win32\lib\Release`
* Put the models into `win32\models`
* Open solution in `win32`(Visual Studio 2010 preferred)
* Build
* Put `IntraFaceDLL.dll` into `win32\Release` and `IntraFaceDLLd.dll` into `win32\Debug`
* Run

For **Linux(x86_64) users**:

* Download this project
* Put IntraFace header files into `linux_x64/include/intraface` 
* Put `libintraface.a` into `linux_x64/lib/intraface`
* Put the models into `linux_64/models`
* Open terminal in `linux_x64`
* make
* Run demo in `./bin`
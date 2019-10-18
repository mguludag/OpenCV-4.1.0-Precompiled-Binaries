# OpenCV 4.1.0 and contrib modules compiled with Qt 5.13 binaries using MSVC2017x64, MinGW7.3x64 and Unix GCC x64 compiler and created help files for Qt Creator

Hello, I compiled OpenCV from its source for using with Qt and Qt Creator. Everything is set up. 
You can simply download the repo and unzip into C:\ drive then unpack the 7z archive in the doc folder and move this folder and .qch file to Qt Docs *(example: C:\Qt\Qt5.13.0\Docs\Qt-5.13.0)* folder inside your Qt installation folder. Thats it!

## How to use in your Qt Projects and Qt Creator?
### On Windows:
After the installation completed then open your project file (.pro file) and add this line below:
   

     include(C:/opencv/opencv410.pri)
And Ctrl+S to save this project then its done.

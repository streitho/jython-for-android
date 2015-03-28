A usage guide for testing the Interpreter

# Introduction #

A simple usage guide in all honesty I am not 100 % familiar with everything as this was based off an existing project but this is what I found out in my development

Keep in mind this is just for testing


# Details #

You will need the Android SDK installed to get a shell for your phone

  1. Open your emulator in the terminal using the command **emulator -avd emulatorName**
  1. Open a shell with your emulator online using the command **adb shell**
  1. You will create several directories on your phones sdcard they are as follows **/sdcard/data/jythonroid/** so you will need to make data and jyhonroid folders as well as **/sdcard/data/app/** so you will need to make the app folder in data
  1. after that is done make sure those folders have read/write permissions using the following command **ls -l** is should return **d---rwxr-x**
  1. next enter the following command in the adb shell window **dalvikvm -classpath /data/app/org.python.util.apk org.python.util.jython**
  1. This should return a prompt for Jython on your phone

And that is it cheers
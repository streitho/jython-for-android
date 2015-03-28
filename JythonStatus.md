# Title #

Jython for Android Status as of April 12 2011

# Introduction #

Jythonroid isn't actively being developed on however I am in the process of porting it to the Android SDK 2.1 (which I call Jython For Android) so far there has been much success through trial and error. However there is still some issues which I will outline below.


# Details #

In order to run the interpreter use the following (future reference)

dalvikvm -classpath /data/app/org.python.util.apk org.python.util.jython


# Issues #

  1. Jython/Python version is still 2.1
  1. The interpreter doesn't actually run receive an error NullPointerException

# Updates #

  1. Update 2011/04/13 The interpreter runs in the emulator now still trying to debug it on an Android phone


Cheers
Castle Visual Studio Integration
================================
![](/doc/cvsi.png)

Introduction
------------
See http://jonorossi.com/projects/cvsi/ for screenshots.

Debugging/Developing CVSI
-------------------------
To develop extensions for Visual Studio you will need to install the Visual Studio SDK:
* 2005 - Visual Studio 2005 SDK 4.0
* 2008 - Visual Studio 2008 SDK 1.0
* 2010 - Visual Studio 2010 SDK 1.0
* 2012 - Visual Studio 2012 SDK 1.0
* 2013 - Visual Studio 2013 SDK 1.0

Configure the Visual Studio project to launch the Visual Studio experimental hive:
* Set "Start external program" to "C:\Program Files (x86)\Microsoft Visual Studio 12.0\Common7\IDE\devenv.exe"
* Set "Command line arguments" to "/ranu /rootsuffix Exp"

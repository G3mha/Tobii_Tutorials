# Tobii_Tutorials

Installation tutorial Tobii Eye Tracker 4C® on Mac with Windows 10 or 11 VM (using Parallels Desktop®)
**This tutorial works for both M1 and Intel Macs**

## Download Parallels Desktop®

Go to Parallels Desktop® [website](https://www.parallels.com).

Download the application.

Buy a key to use the application.

## Create VM Windows 10/11

In the control center, click on the `+` to add a new Virtual Machine.

Select the ISO to be used (in this case, Windows 10 or 11).

Complete the installation, with details like amount of RAM and Processing Cores.

## Configure Tobii App on VM

Using the VM, go to Tobii's website download center [here](https://gaming.tobii.com/getstarted).

On `Select the hardware` click on `Tobii EyeTracking`.

On `Select Tobii device` click on `Tobii Eye Tracker 4C`.

On `Select application` click on `Tobii Eye Tracking Software Core` and click on `Download`.

Open the .exe file and complete the installation process as usual, but don't run the installed app yet.

Shut down your virtual machine, quit Parallels Desktop® and, if you already connected Tobii Eye Tracker 4C®, disconnect it.

Reconnect Tobii Eye Tracker 4C® to the Mac.

Make sure the Eye Tracker is detected on MacOS:

    Open System Information (Applications > Utilities > System Information), click System Report
    Locate the device `EyeTracker` or similar

Reopen Parallels Desktop® and on the upper bar go to `Parallels symbol` > `Preferences` > `Devices`

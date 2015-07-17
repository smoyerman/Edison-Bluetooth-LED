# Edison-Bluetooth-LED
Pin 13 Bluetooth Control for Intel Edison from an Android Phone

Meant for use on the Intel Edison Arduino Breakout Board

Based off of the SPP-loopback.py script written and maintained by Intel's IoT Group

Before running, make sure to do an 

$ rfkill unblock bluetooth

And to pair your phones as described on the following page:

https://software.intel.com/en-us/articles/connecting-the-intel-edison-board-to-your-android-phone-with-serial-port-profile-spp

After pairing the phones, download the BlueTerm + application from the google play store (totally free) and send 0s and 1s back and forth to toggle the onboard LED on pin 13. 

Feel free to modify or extend this code. 

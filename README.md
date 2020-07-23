# ESP-Home-Configs Information

Information about ESPHome can be found here https://esphome.io/index.html

Below is a list of the included YAML files for flashing ESP Home to your devices.  
You will want to makes some changes to the device names and settings but these YAML’s 
will allow you to set things up very quickly.  The Sonoff Basic will need to be 
flashed using a FTDI if they do not already have ESP Home or another firmware that 
has an upload functionality built in.  The Tuya Lightbulb’s will need a Linux based 
computer and software to upload using WiFi like Tuya Convert.

All files are provided AS-IS without warranty.

Here is a list of the files included as well as a simple description.


Sonoff-AlwaysON.yaml – This will allow you to use a Sonoff Basic (and possibly other 
ESP8266 devices) to control a device that you always want on but may need to reboot.  
I use this for routers, modems and WiFi Access Points.  The initial flash will require an
FTDI adapter if you don't already have one https://amzn.to/2DnCQkB (Amazon affiliate link)


Tuya-Light.yaml - This is made for a Tuya based RGB bulb using an ESP8266 controller.
This config will allow you to automatically turn on a bulb when it is powered but may be
best for use outside of a bedroom unless the switch will be turned off at night.
Tuya convert and it's infrmation can be found here https://github.com/ct-Open-Source/tuya-convert

Merkury-A21.yaml - This is another tuya based bulb with a few changes.  The RGB and White pins are 
different but was not hard to configure.  This is model number MI-BW210-999W found locally at Walmart 
and possibly can be found online as well.  I was able to flash with Tuya convert without issue.
Tuya convert and it's infrmation can be found here https://github.com/ct-Open-Source/tuya-convert


And if you did and want to kick me a couple bones for the repairs on my truck 
(probably a blown head-gasket which is going to really SUCK and honestly I need 
to do a rebuild since it's got over 200K miles on it or just replace which either 
way is going to run about 3000 bucks) 17pEPchqZrjVHv8oN3jKMDZp23A24j4Jj is the place for 
BitCoin.  If you want to rather make a donation through Amazon (it doesn't cost you a dime) 
just click on here https://amzn.to/2v74aiY (Amazon affiliate link) before you make an order.  
Or you can make a direct donation here https://www.buymeacoffee.com/Slw0NRx



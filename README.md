# LibrebootTutorial
A small introduction and tutorial on some of the techniques used to disable Intel Management Engine in certain devices. This will be a brief overview of certain techniques involved in the process of Librebooting a machine. As always, continue at your own risk. I am not liable for any damage you cause to hardware, I will provide some sources in this documentation for further research.

As always, more information on hardware specifications and firmware may be found at: https://libreboot.org/

Why would you want to disable to Intel Management Engine? There are certain vulnerabilities found in older firmware versions of the BIOS that may be used as attack vectors to escalate privileges. Here are some sources below you can look at:
https://www.intel.com/content/www/us/en/security-center/advisory/intel-sa-00075.html
https://www.intel.com/content/www/us/en/support/articles/000025619/software.html

Tools Required: This will solely depend on the hardware. To find out the specific hardware you need for Libreboot, be sure to check this documentation: https://libreboot.org/docs/hardware/
Some devices do not require any external devices to flash the BIOS, and it can be simply done by software (Such as the Thinkpad X200). Some devices will require certain hardware to flash the BIOS chip, and it depends on how the motherboard of the device is designed. A difference to be aware of is the type of flash chip used. 
!{Image1}(SOP8-SOP16-1T.jpg)

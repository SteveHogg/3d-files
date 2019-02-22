                   .:                     :,                                          
,:::::::: ::`      :::                   :::                                          
,:::::::: ::`      :::                   :::                                          
.,,:::,,, ::`.:,   ... .. .:,     .:. ..`... ..`   ..   .:,    .. ::  .::,     .:,`   
   ,::    :::::::  ::, :::::::  `:::::::.,:: :::  ::: .::::::  ::::: ::::::  .::::::  
   ,::    :::::::: ::, :::::::: ::::::::.,:: :::  ::: :::,:::, ::::: ::::::, :::::::: 
   ,::    :::  ::: ::, :::  :::`::.  :::.,::  ::,`::`:::   ::: :::  `::,`   :::   ::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  :::::: ::::::::: ::`   :::::: ::::::::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  .::::: ::::::::: ::`    ::::::::::::::: 
   ,::    ::.  ::: ::, ::`  ::: ::: `:::.,::   ::::  :::`  ,,, ::`  .::  :::.::.  ,,, 
   ,::    ::.  ::: ::, ::`  ::: ::::::::.,::   ::::   :::::::` ::`   ::::::: :::::::. 
   ,::    ::.  ::: ::, ::`  :::  :::::::`,::    ::.    :::::`  ::`   ::::::   :::::.  
                                ::,  ,::                               ``             
                                ::::::::                                              
                                 ::::::                                               
                                  `,,`


http://www.thingiverse.com/thing:3127643
Prusa I3 MK3 OctoPrint Raspberry Pi 3+ Einsy Case by lab27 is licensed under the Creative Commons - Attribution - Non-Commercial license.
http://creativecommons.org/licenses/by-nc/3.0/

# Summary

This is a rebuild of the Original Prusa Einsy case that includes an integrated Raspberry Pi 3+ housing. The Raspberry Pi is mounted upside down to the bottom of the Einsy case and connected directly to the Einsy Pi header.

Why a Raspberry Pi 3 and not a Zero? The MK3 is designed with the Pi Zero in mind, unfortunately the Pi Zero has a single-core 1GHz ARM CPU and if you want to use the camera and other features the Pi Zero has not enough juice and your prints will suffer. Gina Häußge, the maintainer of OctoPrint is also discouraging using the Pi Zero for OctoPrint.

Update: Added a Multi Material Upgrade 2.0 Einsy base option to the files which includes a cutout for the MMU2 cable.

Features:
• One case for Einsy and Raspberry Pi
• Detachable Pi case (only one screw)
• Raspberry Pi powered from the Einsy 5V supply
• Direct serial link from Einsy board to Pi (no USB connection needed)
• Flat ribbon cable slot for Raspberry Pi camera
• No additional cables outside the case
• All USB ports and the wired network are accessible from the back

What you need:
• Raspberry Pi and a SD card with OctoPrint
• 1 x M3x18mm (spare parts set)
• 2 x M3x10mm (spare parts set)
• 1 x M3 square nut (spare parts set)
• 3 x M3x5mm for the Raspberry Pi
• 2 x Replacement cable ties (spare parts)
• Cable to connect the Einsy Pi header to the Raspberry Pi header

You can find further information about the cable layout at:
https://shop.prusa3d.com/forum/others-archive--f66/pin-header-for-pi-zero-w-install-t12363-s20.html#p56909

And further info on how to setup OctoPrint with a Raspberry Pi at:
https://help.prusa3d.com/l/en/article/Loz15FAgEk-octo-print-raspberry-pi-zero-w

The Raspberry Pi case should theoretically also work with Raspberry Pi 2. I haven't tested it, would love to hear from someone that can confirm it.

The Raspberry Pi is powered by the printer, so if you power off the printer you will also power off the Pi. To prevent corrupted SD cards, you should first shutdown the Pi via the OctoPrint UI before shutting down the printer. 
There are a couple of Pi USV hats out there, will have to do some more experiments to incorporate one of them. Since the Pi is mounted upside down there should be enough space to mount one of those hats.

Also check out the _Prusa I3 MK3 Raspberry Pi Camera Mount_ that works great with this case. (https://www.thingiverse.com/thing:3121052)

_Let me know if you have any improvements to the design._

_Please post photos if you make this!_


# Print Settings

Printer Brand: Prusa
Printer: i3 MK3
Rafts: No
Supports: No
Infill: 40%
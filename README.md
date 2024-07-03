# sBITX-toolbox
sBITX Toolbox is a collection of utilities and accessory applications for the sBitx transceiver created by W9JES.


![toolbox image](toolbox.jpg)


-----

***PLEASE NOTE: UPGRADING FROM A VERSION PRIOR TO 2.0 REQUIRES UNINSTALLATION OF THE TOOLBOX. SEE THE TROUBLESHOOTING SECTION IN THE GUIDE FOR INSTRUCTIONS.***


What does sBITX Toolbox offer?

- sBITX Launcher: A convenient launcher style application that allows you to add, remove, or open apps with the click of a button.
- sBITX Backlight Control: A touchscreen application to control the screen brightness for power conservation and eye comfort.
- sBITX EZ Data: Application to manage configuration backups.
- sBITX Log Exporter: An application that allows logs to be selected and downloaded in ADIF.
- sBITX Macro Manager: An application to create, edit, and copy macros using predefined macros.
- sBITX Manager: An application that can be used to store/recall frequency memories and provide auxiliary control of the transceiver.
- sBITX Scanner: An application that scans frequency ranges aiding in finding activity.
- sBITX Screen Resizer: A touchscreen application to change the default window size for better scrolling such as using WSJT-X and fldigi natively on the transceiver.
- sBitx Time Sync: A utility that checks your time offset and syncs the system clock to a network time source.
- sBitx Time Keeper: A utility that syncs the real-time clock (RTC) module inside your sBitx transceiver to the system clock or
accurate time source. Useful for off-network communications and data modes.
- sBITX USB Headset Controller: An application that allows you to use USB audio devices like a headset, headphones, or microphone.
- sBITX Voice Keyer: An application that allows you to record, store, and transmit prerecorded voice messages commonly used for
contests, DXing, POTA activations.etc with the press of a button.


**Please note that sBITX-toolbox is currently compiled as a 32bit application designed for the orignal sBitx operating system. We offer a 64bit version [HERE](https://github.com/drexjj/sBITX-toolbox64).**

-----

Windows Versions
-----

Click the link if you are looking for the Windows version of sBITX Manager and sBITX Scanner  [Releases](https://github.com/drexjj/sBITX-toolbox/releases).

-----

Installation
-----

Install on you sBITX:

Open terminal and type
```console
cd $HOME && git clone https://github.com/drexjj/sBITX-toolbox.git && cd sBITX-toolbox && chmod +x *.sh && ./installer.sh
```

Upgrade
-----

If you encounter problems upgrading to v2.6, then please run this command from terminal.


```console
cd $HOME && cd sBITX-toolbox && git stash && git pull && chmod +x *.sh && ./upgrade.sh
```
Now run sBitx Toolbox and use the Update --> Check For Updates function again.

-----

Instruction Guide
-----

The detailed instruction guide is now in PDF format and is located at [Instruction Guide](https://github.com/drexjj/sBITX-toolbox/blob/main/sBITX%20Toolbox%20Guide%20%20v2.7.pdf)

Release Notes are available at [Release Notes](https://github.com/drexjj/sBITX-toolbox/blob/main/release_notes.txt)

-----


Become A Supporter
-----
If you find sBITX Toolbox valuable or have benefited from using it, consider supporting us. Every donation, big or small, helps us keep the lights on and the code flowing.

🌟 [Donate](https://www.paypal.com/donate/?hosted_button_id=SWPB76LVNUHEY) 🌟


Not in a position to donate? No worries! Contributing code, documentation, or simply spreading the word about sBITX Toolbox also goes a long way.

Thank you for your support and belief in my project!



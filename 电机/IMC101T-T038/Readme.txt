Binary file for iMOTION(TM) Motion Control Engine (MCE):
===========================================================

This binary file is encrypted and has been locked to the respective chip ID.
It can only be installed at the exactly matching device type. E.g. an image for 
the IMC101T-T038 cannot be installed at IMC101T-F064.

Where to find the tools
-----------------------
All tools mentioned here can be downloaded from the Infineon iMOTION(TM) web site:

- go to http://www.infineon.com/iMOTION-software
- click on '+ Development Tools' to open the section


Installation with MCEDesigner
-----------------------------
MCEDesigner is the tool to program, configure, tune, and run the iMOTION device.

1. Unpack the contents of this MCE zip file
2. Connect the iMOTION(TM) device via on-board USB link or iMOTION(TM) Link debug box
3. Start MCEDesigner by double-click at the matching .irc file (e.g. IMC101T_V1.00.00.irc)
4. Click into window "System" and the system related menu appears
5. Select the COM port at menu item Preferences - Connection
6. Open the programmer dialog at menu item Tools - Programmer
7. In the programmer dialog 
  a. select "Firmware and Parameter"
  b. enter or browse for the parameter file (e.g. IMC101T-F064_Parameter.txt)
  c. enter or browse for the encrypted binary file (e.g. IMC101T-F064_A_V1.00.00.ldf)
  d. click to button [Start]
8. After programming the IC the MCEDesigner connects automatically and iMOTION MCE is ready to use 


Getting started with iMOTION(TM) MCE
------------------------------------
The MCE firmware image does not contain any motor or system parameters.

- Use MCEWizard to create an initial set of parameters especially adjusted for your 
  motor and power stage
- Use MCEDesigner to program the parameter set to the iMOTION controller, to start
  and stop the drive, and to monitor & fine-tune the performance of the drive


Where to find the MCE Reference Manual
--------------------------------------
All documents mentioned here can be downloaded from the Infineon iMOTION(TM) web site:

- go to http://www.infineon.com/iMOTION-documents
- click on '+ User Manual' to open the section

Reference Manual: Infineon-MCESW-RM-v01_03-EN.pdf


Where to find the Device Datasheet
----------------------------------
All datasheets for the individual devices can be downloaded from the Infineon iMOTION(TM) web site:

- go to http://www.infineon.com/iMOTION
- Scroll down to Products section
- Search for the device in the table
- click on the device name in the leftmost column
- On the device specific web site click on the device name next to the pdf icon

Device Datasheet: e.g. Infineon-IMC100-DS-v01_00-EN.pdf

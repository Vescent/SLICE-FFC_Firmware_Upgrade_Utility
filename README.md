# SLICE-FFC_Firmware_Upgrade_Utility
Utility for upgrading firmware in Vescent SLICE and Fiber-based Frequency Comb products
## NOTE:
  If you have used versions of a Vescent firmware upgrade utility older than V 1.23 on your PC please read and follow the instructions in     
  https://github.com/Vescent/SLICE-FFC_Firmware_Upgrade_Utility/blob/main/Removal_Of_Previous_DFU_Driver_Instructions.pdf

## Instructions
  Left click on SLICE_Firmware_Update_Instructions.pdf and then click 'Download' to download the instructions for use.

  Left click on the SLICE_Firmware_Upgrader-1-44-WIN.zip file and then click 'Download' to download the upgrade utility to your hard drive.

  Optional: If it is desired to use the firmware upgrader on a PC without internet access, Left click on the SLICE_MODELS.cfg file and then click 'Download'. Place this file in the same directory as the SLICE_Firmware_Upgrader-1-44-WIN.exe file.
  
  The upgrade utility can be run from anywhere on your PC

## Configuration 1.44
  1) Checks more COM Ports.
  2) Safety features.
  3) Minor aesthetic improvements to some printouts.
## Configuration 1.42
  1) Removes hard coded model information from the code base and into a separate SLICE_MODELS.cfg file that can be appended with new models as they become available.
  2) Removes the code size limitations for System Controller and ICE2 Firmware.
## Configuration 1.23
  Fixes a bug where, on recent versions of Windows 10, the presence of some Serial devices caused problems with the upgrader detecting the Vescent Products.
## Configuration 1.21
  1) Adds a recovery mode to allow a failed upgrade to be repeated instead of leaving the SLICE inoperable.  
  2) Adds the ability to fetch the latest firmware from Vescent’s Git Hub website to eliminate the need  
     for the user to download the upgrade files and create the directory to put them in.
  3) Allows choosing local upgrade files or the latest files from Vescent’s Git Hub website.  
  4) Adds the ability to select which device to upgrade when multiple SLICE devices are attached to the same PC  
  5) Adds a check to make sure the SLICE restarts correctly after the System Controller upgrade completes.  
     If the SLICE fails to restart, the user is presented with instructions to power cycle the SLICE
  6) Adds the ability to load ICE2 firmware when only bootloader code is in the ICE2’s code space. 
## Configuration 1.11
  Adds a check to make sure a System Controller firmware file is in the upgrade directory.  
  Version 1.10 would miss this and erase the SystemeController without upgrading it.
## Configuration 1.10
  Fixes issues encountered on some Windows 10 machines that caused failures due to the inability to switch to firmware upgrade mode from virtual COM port mode.
## Configuration 1.7
  Initial Release  
  

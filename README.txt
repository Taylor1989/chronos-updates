#Installation
- Install git-lfs if not installed.
	- Ubuntu: `sudo apt-get install git-lfs`.
- Clone this repository. `git clone git@github.com:krontech/chronos-updates.git`. `cd chronos-updates`.
- Make the update. `make`.
- Copy the `camUpdate` folder to a USB stick, or more properly extract camUpdate*.zip which contains the `camUpdate` folder and a few other files.

#Application
-Unzip the Zip file into the root directory of a FAT32 formatted USB stick
	This should result in a camUpdate folder in the root directory of the stick
-Boot up the camera and insert the USB stick
-Backup your calibration data. Tap "Backup calibration data" and wait for this to complete (about 5 seconds). The cal data is now backed up on the USB drive as cal_[serial number].tar
-To install the update, tap Apply Software Update
-A message box should pop up indicating the software update was found. Tap Yes to install the update.
-The screen will go blank for a few seconds, then the updated application will start.
-Done! No need to restart the camera.

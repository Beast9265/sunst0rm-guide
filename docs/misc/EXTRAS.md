# Extras

## How to install Cydia alongside Sileo | A tutorial on how to install Cydia alongside Sileo if you don't like Sileo

Step 1. Install Sideloadly on your Mac from https://sideloadly.io/

Step 2. Go to https://taurine.app/ and download the Taurine iPA

Step 3. Connect your iPhone to your Mac

Step 4. Open Sideloadly and Sideload the Taurine iPA

Step 5. Open your iPhone and trust in Settings > General > Device Management > the profile with your email on it

Step 6. Open Taurine and follow the onscreen instructions to Jailbreak

Step 7. Once it Jailbreaked, there should be an app named Sileo

Step 8. Open Sileo, and click on the search icon on the bottom right of the screen.

Step 9. Search "Cydia Installer", click on that and click install.

Step 10. Click respring

Step 11. Congrats you now have Cydia!

##### Made by NotDavid#3035

## How to prevent your iPhone that you just downgraded to shutdown when on low battery.

Step 1. Open Cydia

Step 2. Press the search icon in the bottom right of the screen

Step 3. Search "Sentinel"

Step 4. Press on it and install it

Step 5. Respring

Step 6. Go to settings and scroll down until you find "Sentinel"

Step 7. Click on it

Step 8. Configure the settings to your liking!

Step 9. Enjoy your Downgraded iDevice

##### Made by NotDavid#3035

## A workaround for the sleep bug. ##
***Note: You need to be in a jailbroken state.***
**Note: This may cause unnecessary battery drain due to keeping WiFi always running.**
Step 1: Open Sileo or your preferred package manager.
Step 2: Add this repo to your sources `https://julioverne.github.io`
Step 3: Search for "Fiona" and install the tweak
**And that is it you are done.**

## Fix Camera TEMPORARY at the moment ##
***Note: You need be in a jailbroken state.***

Step 1: Jailbreak your device with Taurine

Step 2: Make the repo updates in Sileo

Step 3: Install "NewTerm 2" from [Chariz repo](https://repo.chariz.com/)

Step 4: Open NewTerm 2

Step 5: Write " sudo ldrestart " 

Step 6: Tap return

Step 7: Write your root password, must be "alpine" at first (its the primary password, you can change it with writing " passwd " to NewTerm 2)

Step 8: Enjoy

***Note: If the camera still blank, reboot your phone with how you boot in sunst0rm and restart process from Step 4.***

***Note: You need to run process everytime from Step 4 if you want the use camera when it go blank until developers find a fix.***

## Fix Flashlight PERMANENT ##

***Note: This also fixes the logos like recovery,battery.***

Step 1: Download the latest signed version for your iDevice as well as the version you're going to from [ipsw.me](https://ipsw.me/)

Step 2: Rename the ipsw's type to zip type ( ios14.ipsw > ios14.zip, ios15.ipsw > ios15.zip )

Step 2: Extract them with some tool ( ios14.zip > ios14, ios15.zip > ios15 )

Step 3: Open the /Firmware/all_flash in iOS 15.6.1 or ur latest signed firmware zip

Step 3.1: Open the /Firmware/all_flash in iOS 14.x or where u going to zip

Step 4: In 15.6.1 ipsw, delete the files like " DeviceTree.xxxap.im4p " (example for my iPhone 6s, i need delete DeviceTree.n71map.im4p and DeviceTree.n71ap.im4p)


***WARNING: Be sure you not taked DeviceTree from 15.6.1 ipsw. Otherwise the restore will finish unsuccessful!***


Step 5: Copy all remaining files to iOS 14 all_flash path

Step 6: If Operating System asks for overwrite OK it

Step 7: Compress the iOS 14 folder to zip ( ios14 > ios14.zip )

Step 8: Rename zip type to ipsw type ( ios14.zip > ios14.ipsw )

Step 9: From here you can downgrade on sunst0rm with ipsw you do, enjoy.

## Fix Hey Siri, Raise to Wake (Not tested) ##

***Note: Thats how is it in title. Its not tested but you will succeeded in restore and they must work.

Step 1: Download the latest signed version for your iDevice as well as the version you're going to from [ipsw.me](https://ipsw.me/)

Step 2: Rename the ipsw's type to zip type ( ios14.ipsw > ios14.zip, ios15.ipsw > ios15.zip )

Step 2: Extract them with some tool ( ios14.zip > ios14, ios15.zip > ios15 )

Step 3: Open the /Firmware/AOP folder in iOS 15.6.1 or ur latest signed firmware zip

Step 3.1: Open the /Firmware/AOP in folder iOS 14.x or where u going to zip too

Step 4: In 15.6.1 /Firmware/AOP, there must be a file named ' aopfw-xxxxaop.im4p ' (for my iPhone 6S its like ' aopfw-s8000aop.im4p ')

Step 5: Copy that file ' aopfw-xxxxaop.im4p '

Step 6: Replace it to /Firmware/AOP in ***IOS 14 ZIP!***

Step 6.1: If Operating System asks for overwrite OK it

Step 7: Compress the iOS 14 folder to zip ( ios14 > ios14.zip )

Step 8: Rename zip type to ipsw type ( ios14.zip > ios14.ipsw )

Step 9: From here you can downgrade on sunst0rm with ipsw you do, enjoy.








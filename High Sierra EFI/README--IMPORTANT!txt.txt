These are notes intended for myself.
Delete this file from the folder once the steps are completed •̀ᴗ•́

The 'High Sierra EFI' folder in this repo should be placed inside the EFI partition of a USB alongside a folder called 'com.apple.recovery.boot', containing the High Sierra installer (I've tested both the Online/Offline installers and both will work fine).

USB Should look like this:

◈ USB's EFI Partition 
   ├── com.apple.recovery.boot (Contains High Sierra installer, see Dortania guide)
   └── EFI <---- Place 'High Sierra EFI' here and rename it to just 'EFI'
        ├──BOOT 
        └──OC

After install, click Apple logo  --> About this Mac --> Software Update --> Install

Then just install nVidia web-drivers from tonymacx86 or w/e.
Reminder to delete this file ;)

- ross 2022 ☺︎
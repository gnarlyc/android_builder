Welcome to Android Builder v.4.2
Created by gnarlyc (xda-developers.com)
Modified by kiel123 (xda-developers.com)

Thanks/Credits

Gnarlyc               Creator of Android Builder
dsixda                Creator of HTC Android Kitchen
Armin Coralic         Allowing Use of Their Code
cteneyck              Allowing Use of Their Code
xda-developers.com    For Everything

Install

Extract/Copy  AB (folder) + AndroidBuilder.plugin to 
Plugin directory of dsixda's HTC Android Kitchen

scripts/plugins/ (place files here)


CHANGELOG -
v.4.2 - Added option to compile generic aosp without kernel. 
      - Moved Sources and other downloaded files from AB to Builder Directory. Script would take a long time to load when             sources and other files were in AB. 
      - Added About section with credits
      - 

v.4.1 - (unreleased) modified script to work from within android kitchen plugin directory. 
      - added sudo to java switching. 
      - Made all folders and files Download into AB directory
      - Removed use of KITCHEN_ROOT ...had some issues where files were being created in system root folder
      - Renamed and modified abmenu
      - Removed install and bkup scripts

v.4   - re-wrote to add structure to support more devices in the future
      - added option for Cupcake, Donut, and Froyo
      - added .config files that enable touchscreen in kernel by default
v.3   - unreleased build
v.2   - corrected misspellings in code and dialogs
      - added sudo to launch setup script (Still need to sudo bash first. Sorry.)
v.1   - initial release

To-Do
- Implement Update Check Functionality
- Disclaimer? maybe ... 
- Clean Up and make script more universal
- Add More Device Support (Moto Cliq, HTC Dream/G1 + more)
- Work on java 5/6 Switching in 10.4 ubuntu
- add support to use already downloaded kernel source
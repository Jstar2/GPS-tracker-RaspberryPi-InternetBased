# GPS-tracker-RaspberryPi-Online-Dashboard
--------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Description
A Raspberry-pi based GPS tracking device allows users to have pin point tracking device with python3 script.

# Key info before building device.
Device require internet connection which can be provided by LTE, USB-internet device, WIFI etc. Accuracy will be depending on the GPS module you choose.

# Hardware requrement list
1)- Raspberry-Pi (3 or newer versions )

2)- GPS module (With USB connectivity)

3)- Power bank battery pack (with 5volt output)

# Preparing Raspberry-PI envoirment
Preperation in steps as following: 

Step1: Install Oprating system for your raspberry-pi (raspbian lite is recommended, However, any linux based system is fine too)

step2: Install required libraries and update Operating System. (command to install all libraries requred: sudo apt update && sudo apt upgrade -y && sudo apt autoremove -y && sudo apt clean && sudo apt install python3 -y && sudo -H pip3 install gps3 && sudo pip install ubidots==1.6.6 && pip install requests && sudo apt install time -y)

Step3: Test your raspberry-pi and GPS module make sure its running before you start coding (link to test your USB based GPS module https://wiki.52pi.com/index.php?title=EZ-0048). make sure to update your Oprating system (command to update your Operating System: sudo apt update && sudo apt upgrade -y && sudo apt autoremove -y && sudo apt clean)

Step4: Create an account on ubidots website. create a device on ubidots and get token ID.

Step5: Creating python 3 script (find script in a project folder named: tracker_Script). Make sure that you plug in the token ID in the script which will be maked in the script clearly.

Step6: Create ubidots dashboard as desired.

All Done.

# Future Ideas
- 3d printed case could be built
- Device could be attached with a car if internet is provided with the device. 
- A radio wave device could be attached for coverage to some geographical area. 
- Device could be used for tracking journes 
- Whole project could be converted to raspberry-pi pico with internet connection module
- Many more things could be done.

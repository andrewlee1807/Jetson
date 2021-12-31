# Requirements
Before you get started, you'll need the following:
1. SD card with storage higher 64 GB (By default, the tegraflash package for the AGX Xavier is set up for flashing the on-board eMMC.)
2. PC running Ubuntu Desktop (18.04): installed Nvidia’s SDK Manager
3. (Optional) Windows: installed SD card formatter
4. A suitable USB cable. For most Jetsons, this is a type A to micro-B cable, but for the AGX Xavier dev kit, you'll need a USB-C cable. As NVIDIA mentions in their documentation, it's important to use a good-quality cable for successful flashing. connect directly to a port on your system, rather than using a USB hub.
5. Internet Connection

# Step by Step initialization
## 1.	(Windows) Prepare the SD card and format with “SD card formatter” application on Windows.
![img_2.png](img_2.png)
## 2.	(Ubuntu 18.04) Using a Linux PC, then run  Download the latest version of Nvidia’s SDK Manager on a PC running Ubuntu 18.04.
![img_1.png](img_1.png)
![img_3.png](img_3.png)
![img_4.png](img_4.png)
![img_5.png](img_5.png)
During the install, make sure to plug a keyboard and monitor into the Jetson. On first boot, it will go through the usual Ubuntu setup steps. Accept the Licenses.
## 3.	(Jetson AGX Xavier) Setup and turn on Jetson AGX Xavier:
![img_7.png](img_7.png)
-	Connect Jetson to Ubuntu PC (currently running SDK Manager) by Cable (type C to type A).
-	Don’t forget to insert the HDMI, Mouse and Keyboard.
## 4.	(Ubuntu 18.04) Waiting the process.
- Until SDK Manager run to this screen:
![img_9.png](img_9.png)
- Then change the option setting to “Manual”:
![img_10.png](img_10.png)
-	Remember to do **Plug in** (Cable usb type C to type A) to Ubuntu.
## 5.	(Jetson AGX Xavier): Power on the Jetson and put it into recovery mode. Holding 2 buttons to 2 seconds.
![img_11.png](img_11.png)
Press and hold the center button, and press and release the reset button (on the right). AGX Xavier buttons.
![img_12.png](img_12.png)
## 6.	(Ubuntu 18.04) Click the Flash
![img_13.png](img_13.png)
## 7.	(Jetson AGX Xavier) Setup the Username. Passwd Jetson
![img_14.png](img_14.png)
.
.
.
![img_15.png](img_15.png)
## 8.	(Jetson AGX Xavier) After initialing the OS, please insert the internet (USB internet/ Cable) and check the IP address to use next step.
![img_16.png](img_16.png)

## 9.	(Ubuntu 18.04) Enter the correctly Jetson’s IP as well as username, passwd.
![img_17.png](img_17.png)
## 10.	Waiting
![img_18.png](img_18.png)
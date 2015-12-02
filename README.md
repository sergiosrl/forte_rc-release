# forte_rc-release
 ROS Release Repository for forte_rc package maintained by Ingeniarius

[FORTE-RC](http://ingeniarius.pt/?page=forterc) is a mobile robotic platform designed for research in the field of social robotics. FORTE-RC is a robust omnidirectional platform that can carry more than 100kg - ideal for transporting heavy loads or even a person in indoor facilities.

# 1.	Install
Forte-RC is equipped with a Intel NUC NUC5i5RYH to run the high level of programming and a Arduino Mega ADK to run the low level.

## 1.1 Accessing Intel NUC5i5RYH
To access FORTE-RC internal [CPU](http://www.intel.com/content/www/us/en/nuc/nuc-kit-nuc5i5ryh.html), you need to connect to it first. Two ways of doing it:
- Work directly on FORTE-RC touchscreen
- acess NUC with NoMachine remote desktop software

### 1.1.1 Instal and connect NoMachine
 1. Download and install NoMachine on you own computer [NoMachine](https://www.nomachine.com/download|NoMachine download page)
 2. In case FORTE-RC is already connected to the same wireless network than you, then jump to step 6
 3. Check for available wireless networks and connect to the one with SSID `Forte-Ap`
 4. Introduce the following password: `1234567890`
 5. Connect to FORTE-RC using NoMachine, under the IP `10.42.0.1`, using `nuc` as both username and password, then jump to step 7
 6. If you are connected to the same network than FORTE-RC, you will be able to see it through NoMachine, and you just have to connect to it, using **_nuc_** as both username and password
 7. That's it - Enjoy!

# 2 FORTE-RC Description
it's provided URDF files for simulation enviroment [here](http://ingeniarius.pt/ros/FORTE_ROSv10.zip)

SCREENSHOT of simulation enviroment


![alt text](http://ingeniarius.pt/ros/Forte.png "Logo Title Text 1")

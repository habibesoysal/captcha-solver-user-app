# Captcha solver user app
This application will solve captcha for you using `java.awt.Robot` class. **Do not move mouse or use your keyboard when this app is solving recaptcha**

To run this app, open project folder in Intellij and go through all TODOs.

* #### //TODO 1) give read and write permission this hosts file
You have to give read and write permission to hosts file. For windows you can right click on hosts file, click on properties and goto Security. You can assign read write and execute permission to this file.

For linux systems you can give rw permission using `chmod 600 /etc/hosts` command.

* #### //TODO 2) this is the location of captcha checkbox appear on web page. You have to update this location according to your screen
      robot.mouseMove(100, 180);
  This is the location on screen where robot will click and get the captcha response. This will work on most of the screens, if it doesn't, then you have to find the coordinates and give it here.
  How to find ordinates ![Check This](/screen.png)
  
* #### TODO 3) this is the captcha-solver-server-url. You can use local IP address instead of domain
You can enter **Captcha solver server url** instead of http://captcha-server-by-niranjan.com:9990/. If you are running server app on same system, then you can enter http://localhost:9990/ or http://127.0.0.1:9990/ here.

* #### //TODO 4) Hard coded path of chrome for windows. Change it according to your system
      C:/Program Files (x86)/Google/Chrome/Application/chrome.exe
I've added chrome path for windows here. You can check if this is the correct path, if its not then you can find chrome.exe in your system and update your path here.


After going through above changes, run Application.java file and check if JFrame is displayed.


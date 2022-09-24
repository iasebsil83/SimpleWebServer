# **Simple Web Server**

***Your own web server, in only one command.*** 

&nbsp;

&nbsp;

## Requirements

- **Linux Operating System**<br>
This program has been made to run on linux systems only.

- **Package : Apache 2**<br>
You need to have apache2 to install your web server.<br>
It can be installed by using command :
```bash
sudo apt install apache2
```

&nbsp;



## Install

Open a terminal inside the main folder and run program **install** :
```bash
sudo ./install
```
Note that you will need root privileges to run it.

&nbsp;



## Uninstall

Open a terminal inside main folder and run program **uninstall** :
```bash
sudo ./uninstall
```
Note that you will also need root privileges to run it.

&nbsp;



## Configure

Your server can be configured using file *conf/user.conf*.

After each modification of this file, you will need to restart your server to apply changes.

*NOTE:* You can use program **restart** to do it.
      It is just executing program **stop** and then **start** one more time.

&nbsp;



## Start/Stop Web Server

- **Start web server**

Open a terminal into your main folder and run program **start** :
```bash
./start
```

Your server is running.
The file *user.conf* contains all the information concerning your web server (address, port...).

&nbsp;

- **Stop web server**

Open a terminal into your main folder and run program **stop** :
```bash
./stop
```

&nbsp;

Tips: For the moment, each time you change your server name, the links of your website still exists in your system.
      To remove them quickly, execute program **remove**.
      This behaviour will change soon in order to be automatic at each server **start**.

&nbsp;

&nbsp;

***Your web server is ready to go !***

&nbsp;

## Last Note

This program is based on Apache, a free web server application for linux and the simplest to use and configure in my opinion.
For more information about it, please check out their website :

https://apache.org/

This project has been made to be as SIMPLE as possible to use and deploy BUT there is much more things you can configure if you follow their instructions.

&nbsp;

&nbsp;


*Contact     : i.a.sebsil83@gmail.com*<br>
*Youtube     : https://www.youtube.com/user/IAsebsil83*<br>
*GitHub repo : https://github.com/iasebsil83*<br>

Let's Code ! &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;By I.A.

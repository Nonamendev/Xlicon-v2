
<p align="center">  
  <a href="https://chat.whatsapp.com/EjsQvJNcFGVCSfaBEIxZm2">
    <img alt="X-2.0" height="300" src="https://i.ibb.co/L1SGhJy/images.jpg">
    <h1 align="center">XLICON-BOT</h1>
    
  </a>
</p>
<p align="center">
<a href="https://github.com/ahil15"><img title="Author" src="https://img.shields.io/badge/XLICON-BOT-black?style=for-the-badge&logo=whatsapp"></a>
<p/>
<p align="center">
<a href="https://github.com/ahil15?tab=followers"><img title="Followers" src="https://img.shields.io/github/followers/ahil15?label=Followers&style=social"></a>
<a href="https://github.com/ahil15/Xlicon-v2/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/ahil15/Xlicon-v2?&style=social"></a>
<a href="https://github.com/ahil15/Xlicon-v2/network/members"><img title="Fork" src="https://img.shields.io/github/forks/ahil15/Xlicon-v2?style=social"></a>
<a href="https://github.com/ahil15/Xlicon-v2/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/ahil15/Xlicon-v2?label=Watching&style=social"></a>
</p>

## Notice

We request you to Read our full repository or u might get issues at deploying the bot...Developed by Slasher..!!

## Support

For our bot support, Do email [ infiniteytff@gmail.com ] or join our Whatsapp Support Group.

<a href="https://chat.whatsapp.com/EjsQvJNcFGVCSfaBEIxZm2"><img alt="WhatsApp" src="https://img.shields.io/badge/-Whatsapp%20Group-lime?style=for-the-badge&logo=whatsapp&logoColor=white"/></a>
#### SETUP

1. Fork the repo
    <br>
<a href='https://github.com/ahil15/Xlicon-v2/fork' target="_blank"><img alt='Fork repo' src='https://img.shields.io/badge/Fork Repo-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=white&color=black'/></a>

2. Scan the QR and upload ***Creds.json*** file to your XLICON-SESSION Folder. You Have to Fork The bot to Use The Bot....( You will recieve the ***Creds.json*** on your bot number after scanning the Qr)
    <br>
<a href='https://replit.com/@ahil15/XLICON-Multi-Session?v=1' target="_blank"><img alt='SCAN QR' src='https://img.shields.io/badge/Scan_qr-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=black&color=black'/></a>


## Installation 

1.⚙️  Edit config file 

- you have to change these if u want to use this bot


- Edit your config details in your own repo like -- [`config.js`](https://github.com/ahil15/Xlicon-v2/blob/master/config.js)
```js

global.Owner = ["8801853262586"]; 
global.OwnerNumber = ["8801853262586"];
global.ownertag = ["8801853262586"];
global.OwnerName = "Slasher";
global.BotName = "X-2.0";

```



.2⚙️ If You Want Autoreply/Bot Chat ⚙️

- It's optional if u want to make auto reply bot like Auna10 you have to do this...

Comment out/delete /* , */ the code form your Core.js line 224 and 332 in your own repo like -- [`Core.js`](https://github.com/ahil15/Xlicon-v2/blob/main/Core.js)
```js  
   
   /*
    Dm and Groups Autoreply/Bot chat

   if (!isCmd && !m.isGroup){

   const botreply = await axios.get(`http://api.brainshop.ai/get?bid=166512&key=5nz1Ha6nS9Zx1MfT&uid=[uid]&msg=[msg]=[${budy}]`)

   txt = `${botreply.data.cnt}`
  m.reply(txt)
  }      
    */
   
```



.3 🛡️ Windows Cmd & Vs 🛡️

* [`Download ffmpeg`](https://ffmpeg.org/download.html#build-windows) and set path
* [`Download wget`](https://eternallybored.org/misc/wget/releases/) and set path
* [`Download Node JS`](https://nodejs.org/en/download/)
* [`Download Git`](https://git-scm.com/downloads)
* [`Download Libwebp`](https://developers.google.com/speed/webp/download)
```cmd
> git clone https://github.com/ahil15/Xlicon-v2.git
```
```
> cd Xlicon-v2
```
```
> npm i
```
```
> npm start
```
#### DEPLOY TO Heroku 

1. Now Deploy
    <br>
<p align="center"><a href="https://heroku.com/deploy?template=https://github.com/ahil15/Xlicon-v2"> <img src="https://img.shields.io/badge/Heroku%20Deploy-purple?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>

</br>     

<h2 align="center"> Add This 2 Builbpacks On Heroku
</h2>

```
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
``` 
```
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```
#### DEPLOY TO Replit 

1. Now Deploy
    <br>
<p align="center"><a href="https://repl.it/github/ahil15/Xlicon-v2"> <img src="https://img.shields.io/badge/replit%20Deploy-black?style=for-the-badge&logo=replit" width="220" height="38.45"/></a></p>

#### DEPLOY TO Codespaces

1. Now Deploy
    <br>
<p align="center"><a href="https://github.com/codespaces/new"> <img src="https://img.shields.io/badge/Codespace%20Deploy-black?style=for-the-badge&logo=codespaces" width="220" height="38.45"/></a></p>

#### DEPLOY TO Railway

1. Now Deploy
    <br>
<p align="center"><a href="https://railway.app/new"> <img src="https://img.shields.io/badge/Railway%20Deploy-green?style=for-the-badge&logo=railway" width="220" height="38.45"/></a></p>

#### DEPLOY TO Mongenius

1. Now Deploy
    <br>
<p align="center"><a href="https://studio.mogenius.com/"> <img src="https://img.shields.io/badge/Mongenius%20Deploy-blue?style=for-the-badge&logo=mongenius" width="220" height="38.45"/></a></p>

#### DEPLOY TO Okteto

1. Now Deploy
    <br>
<p align="center"><a href="https://cloud.okteto.com"> <img src="https://img.shields.io/badge/Okteto%20Deploy-darkblue?style=for-the-badge&logo=okteto" width="220" height="38.45"/></a></p>

<br>
<br>
<br>
<br>
     
     
     
- Termux
```js
termux-setup-storage
```
```
apt update
```
```
apt upgrade
```
```
pkg update && pkg upgrade
```
```
pkg install bash
```
```
pkg install libwebp
```
```
pkg install git -y
```
```
pkg install nodejs -y
```
```
pkg install ffmpeg -y 
```
```
pkg install wget
```
```
pkg install imagemagick -y
```
```
git clone https://github.com/ahil15/Xlicon-v2
```
```
cd Xlicon-v2
```
```
npm i
```
```
npm start
```

- Command For 24/7
```js
npm i -g forever && forever index.js && forever save && forever logs
```

</br></br>
<h1 align="center">  ⭐ Spacial Thanks To ⭐
</h1>

* [`🎐 Kai.!!`](https://github.com/kai0071)
* [`🎐 AsliGuru`](https://github.com/Guru322)
* [`🎐 SuhailTechInfo`](https://github.com/SuhailTechInfo)






</br> 

<h2 align="center">  Reminder
</h2>
   
## 
- This bot is not made by `WhatsApp Inc.` So misusing the bot might `ban` your `WhatsApp account!`(Though your WhatsApp account can be unbanned only once.)
- I am not responsible for banning your account.
- Use at your own risk by keeping this warning in mind.
 


<h1 align="center">
</h1>

</p>
<h1 align="center"> ✧ Thanks To Kai!!!✧
</h1>


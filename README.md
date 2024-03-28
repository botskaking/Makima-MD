<p align="center">
<a href="https://github.com/botskaking/Makima-MD">
    <img src="https://images5.alphacoders.com/126/1264439.jpg">
  </a>

<h1 align="center"> Makima MD
</h1>

<p align="center"> 
Konnichiwa Senpai, I am "Makima" an Opensource WhatsApp bot made by <a href="https://github.com/botska
king">IRONMAN</a> and his team "TRIDENT"
<br>

<p align="center">
  <a href="https://github.com/botskaking/Makima-MD/fork">
    <img src="https://img.shields.io/github/forks/botskaking/Makima-MD?label=Fork&style=social">
    
    
  <a href="https://github.com/botskaking/Makima-MD/stargazers">
    <img src="https://img.shields.io/github/stars/botskaking/Makima-MD?style=social">
  </a>
<p align="center">
<a href="https://github.com/botskaking/Makima-MD/"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fbotskaking%2FMakima-MD&count_bg=%23FFA305&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=People+Visited&edge_flat=false)](https://hits.seeyoufarm.com" width="150px" /></a>
</p>


  
<p align="center">
<a href="https://github.com/botskaking"><img title="Owner" src="https://img.shields.io/badge/Owner-Team TRIDENT-white.svg?style=for-the-badge&logo=github" width="170px"></a>

 <a href="https://github.com/FantoX/Atlas-MD/blob/main/LICENSE.md">
  
<img src='https://img.shields.io/github/license/FantoX/Atlas-MD?color=%231e81b0&style=for-the-badge' width="114px">

<p align="center">
<a href="https://github.com/botskaking"><img title="Open Source" src="https://img.shields.io/badge/Open%20Source-YES-green.svg?style=for-the-badge" width="150px"></a>
<a href="https://github.com/botskaking"><img title="" src="https://img.shields.io/badge/Maintained-YES-green.svg?style=for-the-badge" width="143px"></a>
</p>
<br>

---
 <br>
 
 # 🧩 Deploy Makima
     
<details close>
<summary>Click to choose your favourite platform to Deploy</summary>
 
<br><br>   
    
<h4 align="center"> Deploy on Railway 
</h4>
  
<p align="center">
    <a href="https://railway.app/new/template/Gts2Zx?referralCode=f3gg2m">
    <img src="https://railway.app/button.svg" alt="Deploy on Railway" width="170px">
    </a>
    <br>
    <a href="https://youtu.be/Qs6ryWnEtu8"><img src="https://i.ibb.co/71mYRh4/116-1161192-podcast-subscribe-listen-button-youtube-sign-hd-png.png" alt="Watch tutorial on YouTube" border="0"  width="105">
    </a>
</p>
 
<h4 align="center"> Deploy on Heroku
</h4>

</p>

<p align="center" >
    <a href="https://heroku.com/deploy?template=https://github.com/botskaking/Makima-MD">
    <img src="https://www.herokucdn.com/deploy/button.png" width="160px" alt="Deploy on Heroku">
<br>



</details>



    
    
# 📑 Makima Deploy and Hosting guide

<details close>
<summary>Click to read Deploy Manual</summary>    
    
## ⚛️ Heroku Deploy:
      
- [Fork Main Repo](https://github.com/botskaking/Makima-MD/fork)
- Create a MongoDB URL. Need help? Watch this short 1 minute [Video Guide](https://youtube.com/shorts/pIHvoXkwmq4?feature=share) for MongoDB URL.
- Click on `Deploy to Heroku` button ( `For those who didn't modified bot.`). In other case (`For those who modified bot.`) edit README.md file and chage the repo link of Repl.it deply button from `https://github.com/botskaking/Makima-MD` to your fork URL `https://github.com/<Your GitHub Username>/<Your Makima fork repo name>` also got to `app.json` and change `Website` ans `Repository` link from my link to your link. Then click on `Deploy to Heroku` button.
- Then put these values in environment variables accordint to instructions (Mandatory).
  
<br>
      
KEY | VALUE
-- | --
MODS | Phone numbers in this format (`918279975767`,`918250895584`) without `+` or `SPACE`.
MONGODB | Your MongoDB URL
SESSION_ID | Any random value (`EX: gwfdrte56711`) and `keep it copied`.
PREFIX | Any single special character except `@` (`Ex: . or / or * or , etc.`)
TENOR_API_KEY | Your tenor API key if you have. Or use this public one: `AIzaSyCyouca1_KKy4W_MG1xsPzuku5oa8W358c`
  
<br>
      
- Next start deploy and wait for 3-4 minutes.
- After it's done click on `Manage App`.
- Next go to `Recources` then turn on `Web: npm start` and disable other one `If there is any other button.`
- After that go to More ---> view logs and wait for qr to appear.
- When you see broken QRs are appearing chick on `Open app` and put your Previously copied `Session ID` and click on `Get QR`.
- Scan the QR from WhatsApp ---> Linked devices ---> Link a device.
      
<br><br>      
      
    
      
## 🔷 Railway Deploy:   
- [Fork Main Repo](https://github.com/botskaking/Makima-MD/fork)
- Create a MongoDB URL. Need help? Watch this short 1 minute [Video Guide](https://youtube.com/shorts/pIHvoXkwmq4?feature=share) for MongoDB URL.
- Click on `Deploy to Railway` button ( `For those who didn't modified bot.`). If you modified bot and want to deploy your modified version in Railway then that button will not help you. Go to Railway website and deploy github repo from there manually.
- Those who are deploying through button: Put all necessary details there according to instructions given there.
- Those who are deploying manually from Railway website put these `Enviroment Variables` before start deploying ( Mandatory).
      
<br>
      
KEY | VALUE
-- | --
MODS | Phone numbers in this format (`918279975767`,`918279975767`) without `+` or `SPACE`.
MONGODB | Your MongoDB URL
SESSION_ID | Any random value (`EX: gwfdrte5678`) and `keep it copied`.
PREFIX | Any single special character except `@` (`Ex: . or / or * or , etc.`)
TENOR_API_KEY | Your tenor API key if you have. Or use this public one: `AIzaSyCyouca1_KKy4W_MG1xsPzuku5oa8W358c`
  
<br>      
 
- 5-6 minutes later when Deploy is completed click on that generated domain to go to QR page.
- just put your Previously copied `Session ID` and click on `Get QR`.
- Scan the QR from WhatsApp ---> Linked devices ---> Link a device.
- If you are having issues follow [Railway Deploy Tutorial](https://youtu.be/Qs6ryWnEtu8).
<br><br>
      
  
## 🪟 CMD / VS Code / Powershell / Terminal Deployment Method 

- [Download Updated code](https://github.com/FantoX/Atlas-MD/archive/refs/heads/main.zip) from Main GitHub Repo or Download from your Forked Repo.
- Extract the `.zip` and open Vs code / Cmd / Powershell / Terminal in that directory and give thesse following commands one-by-one:
- Rename `.env.example` to `.env` and fill in the required details in `.env` file and `config.js` (Mandatory).

```
npm i
npm start
```

- To get new QR if you logged out from the WhatsApp linked device section go to `.env` file and change `SESSION_ID` to any random string and save it by clicking on `Commit Changes`.

### ✧ Requirements for CMD/VS code istallation:
- [Node.js](https://nodejs.org/en/download/)
- [Git](https://github.com/git-guides/install-git)
- FFmpeg ( [for Windows](https://www.geeksforgeeks.org/how-to-install-ffmpeg-on-windows/) or [for Linux](https://www.tecmint.com/install-ffmpeg-in-linux/) or [for Mac](https://ffmpeg.org/download.html) )
- Libwebp (Not necesary for Windows).

Note: If you don't pre-install these before CMD / VS code Installation bot will not start!
</br> 

---
<br>  
      

## 🐧 UserLand Deployment Method (Not Recommented a bit)


#### ⚜️ Download `UserLand` application old version ( 3.1.2 ) from [Here](https://m.apkpure.com/userland-linux-on-android/tech.ula/variant/3.1.2-APK).
#### ⚜️ Install `Debian` terminal in userland.
#### ⚜️ Rename `.env.example` to `.env` and fill in the required details in `.env` file and `config.js` (Mandatory).

</p>

### UserLand commands:


```
sudo apt update
sudo apt upgrade
sudo apt install bash
sudo apt-get install libwebp-dev
sudo apt install git
sudo apt install nodejs -y
sudo apt install ffmpeg -y
sudo apt install wget
sudo apt install npm
sudo apt install imagemagick

git clone https://github.com/botskaking/Makima-MD/

ls
cd Makima-MD
npm i


cd
npm install --global yarn
yarn add sharp
sudo apt install curl


curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash -


sudo apt-get install -y nodejs
yarn add sharp
cd Makima-MD
npm i
npm start

``` 
- Note in `git clone <my bot's repo>` section your can use Your customised bot's github link too (For that make sure you [Forked](https://github.com/botskaking/Makima-MD//fork) this repo and modified `.env` file and `config.js`).
- This method will work on most other bots too.

#### 📌 To stop a bot in Userland
- Tap on `CTRL` button then tap on `C` from keyboard

#### 📌 To start bot again ( While you are inside Makima-MD folder {use `cd Makima-MD` to get inside the folder} )
- `npm start` or use `yarn start` to start bot again.


#### 📌 Start bot after UserLand session is cleared
```
cd Makima-MD
npm start
```
#### 📌 What to do if you logged out from the WhatsApp linked device section and want to get new qr to login
- Go to your GitHub fork of this bot and open `.env` file and change `SESSION_ID` to any random string and save it by clicking on `Commit Changes`.
- Then open `UserLand` and run these commands one-by-one:

```
cd Makima-MD
git fetch origin
git merge origin/main
npm start
```


#### ⚜️ Note as UserLand is a physical server so you must keep on your internet connection active to make sure bot works. Otherwise bot will be down.
<br><br>

</details> 
    
<br>
# ⚠️ Warning:
    
- This bot is not made by WhatsApp.inc so overusing this bot may result in WhatsApp account ban.
- We will only assist you in `Bot Deployment ( Installation or Hosting )`. Not in `Bot Development`.
- If you Modify this bot and face any issues, I am not responsible for that because it's not possible for me or my team to help everyone in bot Development / Modification. Only modify if you know what you are doing.
- This bot is made for `Educational / Fun / Group Management` purposes only. I and the team will not be responsible for any misuse of this bot.
- We will only assist you in `Setup / Deployment` of this bot.

<br><br>

# 📛 Legal Disclaimer

- We suggest you to use your `Own MongoDB URL` while deploying inside `.env` or `Environment Variables`. That will increase your Privacy and Security.
- We don't recommend to hardly modify the script. `If you do so, you will be responsible for any issues / bugs and we will not provide any support` as we are also busy in our life.
- We will not be responsible for any issues caused by any individual hosting this bot and cause any harm to any Group `(So don't make someone Group Admin who you don't know just because they are hosting the Bot)`.

<br><br>

---
<br><h2>
<b><i>`THIS BOT IS MODIFICATION VERSION OF`</i></b> <a href='https://github.com/FantoX/Atlas-MD'>Atlas MD</a></h2>

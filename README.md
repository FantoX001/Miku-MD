<p align="center">
   <a href="https://github.com/FantoX001">
    <img src="https://c.tenor.com/NJVFjOYEcsIAAAAC/miku-gotoubun.gif" width="610">
     
</p>
<h1 align="center"> Miku Nakano (Beta)
</h1>
<p align="center"> 
  Konochiwa Senpai, I am "Miku Nakano" a WhatsApp bot made by Fantox to do everything that is possible on WhatsApp based on WhatsApp Multi Device(MD) Support.

<p align="center">
  <a href="https://github.com/FantoX001/Miku-MD/fork">
    <img src="https://img.shields.io/github/forks/FantoX001/Miku-MD?label=Fork&style=social">
    
    
  <a href="https://github.com/FantoX001/Miku-MD/stargazers">
    <img src="https://img.shields.io/github/stars/FantoX001/Miku-MD?style=social">
  </a>

 
<a href="https://github.com/FantoX001">
    <img src="(https://visitor-badge.glitch.me/badge?page_id=https://github.com/FantoX001/Shikimori-MD.visitor-badge&left_text=Total%20Repo%20Visitors)">
  </a>
</br>
      
</br> 
   
## ✧✧ Temporarily little bit Maintained for bug fixes. Thank You so much guys for your love and support 💕. 
</br></br>
  
  
## ✧✧ Setup before deploy (Optional):
### Go to `config.js`
-  To change the `Owner Number`, go to line no `10`, `11` and `12` [ Note there 91 is my country code don't put + or spaces there ]
-  Change `Bot Prefix` in line no `23` inside global.prefa. [ Put anything you want except @ ] 
-  Change `Owner Name` in line no `16`
-  Change `Sticker packname` and `author` in line no `14` and `15`
<br>
<br>

## ✧✧✧ Vulnerability Report (✔️ Fixed on 06/11/2022 -  3:18 pm IST)
- In a recent vulnerability test `( On 04/11/22 - 9:10 am IST )` I found that this bot contains a major vulnerability which can let `your WhatsApp accout be accessed by the Attacker`. Actually every 3rd party things contains some hidden vulnerability but here I am sharing that vulnerability with you as an warning. Which is `only effective if you use repl.it scanner`. [ It will be fixed soon so don't worry. ]

- It can be avoided by installing bot in `Termux`, `VS code` etc. physical deploy methods or using other session generators.
- I made this bot as an open source project but as it's dev I don't want user's account to be hacked. So I am working to fix it as soon as possible.
- Stay safe and stay updated.

<br>

### ✧✧ Update Report (06/11/2022 -  3:18 IST)
- Vulnerability has been `fixed` by me so no worries.
- This bot doesn't contains any security related vulnerabilities anymore. 


<br>
<br>
  
## ✧✧✧ Recent Patch notes
<details close>
<summary>Read recent Patch notes of Miku</summary>
<br>

```
✧ Added Forever worker again and removed pm2.
✧ Fixed Heroku account ban issue.
✧ Added Weather command. [Usage: -weather Kolkata]
✧ Fixed a critical security related vulnerability.
✧ Added single config prefix changing facility.
✧ Added pm2 worker.
✧ Fixed "Play" and related commands.
✧ Added Ytdl-Core.
✧ Added "add" command [Usage: -add 91 810xxxxxxx  where, 91 is country code and other part in number.]
✧ Added "say" command using Text-to-speech [Usage: -say Hello everyone]
✧ Bot can delete other people's messages now. [Condition: Both bot and user must be admin!]
✧ Fixed -hentaivideo command.
✧ Disabled Dm autoreply.
✧ More fixes soon...[Contact me via Telegram or WhatsApp for report or issues].

```

</details>

## ✧✧✧ Why use Miku as your Base?

<br>

```
1. Copyright Free.
2. No Source Code Encryption.
3. Most commands.
4. Singe prefix ("-").
5. Self restoration.
6. No API key needed!
7. Full premission to Recode.
8. Regularly Updating and Improving.
9. Supports Latest WhatsApp, GB, Fouad, Alpha, YoWhatsApp and all other mods (MD).

✧ The main motto of this project is to provide Beginner Devs a base without any limitations 😊.
✧ Check "Credits" section and Support Them too.

-regards FantoX001
```

</br>

## ✧✧✧ Video tutorial for Heroku Deploy:

<a href="https://youtu.be/fZdM7Ahb4JE"><img src="https://i.ibb.co/71mYRh4/116-1161192-podcast-subscribe-listen-button-youtube-sign-hd-png.png" alt="Watch tutorial on YouTube" border="0"  width="160"></a>

Here's the Video Tuturial for Deploying and Hosting Miku Bot on Heroku.

## ✧✧✧ Heroku Deployment Method:

#### ✧ [Fork](https://github.com/FantoX001/Miku-MD/fork) this repo.

#### ✧ Click this scan button below and scan the given QR within 15 seconds from your WhatsApp. 
<a href="https://miku-qr--fantox001.repl.co/"><img src="https://play-lh.googleusercontent.com/901aMQFFnVoX2T-YuJmTIwpPve_SUgMv_QSyzMSPtAqt_l0CyXN1DxfD6xXU0r2f9iM=w240-h480-rw" width="90" />
</a>
#### Or, Scan indirectly from my `repl.it`

#### <a href="https://replit.com/@FantoX001/Miku-QR?v=1"><img src="https://i.ibb.co/pPQjJL2/replit-logo-png-transparent.png" alt="replit-logo-png-transparent" border="0"  width="120"></a>
#### ✧ Download the `session.json` file and upload it on the hompage of your `Fork`.
#### ✧ Go to your [Heroku](https://www.heroku.com/) account.
#### ✧ Create a `random app` in Heroku with any name.
#### ✧ Connect your `GitHub` with `Heroku`
#### ✧ Then connect `Miku's repo` from your GitHub.
#### ✧ Go to Heroku's `settings` ---> `Add Buildpacks` then connect these 3 buildpacks one by one mentionned    below.
#### ✧ Then come back to `Heroku` ---> `Deploy` then deploy the app
#### ✧ After deploy is finished goto `Heroku` ---> `Resources` and turn on the switch.
#### ✧ Enjoy :)


## ✧ Heroku Builbpacks:

```
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
``` 
```
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```
```
heroku/nodejs
```


## ✧✧✧ Join My Whatsapp Group for Support

<a href="https://chat.whatsapp.com/JcBzjRIxM5UHfuJbt0KrWt"><img src="https://img.shields.io/badge/Join Group-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
</a>

## ✧✧✧ CMD Deployment Method (Without downloading this code as .zip)
```
git clone https://github.com/FantoX001/Miku-MD.git
cd Miku-MD
npm i
npm start
```

## ✧✧✧ CMD  / VS code Deployment Method (After downloading this code as .zip)
- Extract the .zip and open Vs code / Cmd in that directory and give thesse following commands one-by-one:
```
npm i
npm start
```


### ✧ Requirements for CMD/VS code istallation:
- [Node.js](https://nodejs.org/en/download/)
- [Git](https://github.com/git-guides/install-git)
- FFmpeg ( [for Windows](https://www.geeksforgeeks.org/how-to-install-ffmpeg-on-windows/) or [for Linux](https://www.tecmint.com/install-ffmpeg-in-linux/) or [for Mac](https://ffmpeg.org/download.html) )
- Libwebp

Note: If you don't pre-install these plugins before CMD / VS code Installation bot will not start!
</br> 

## ✧✧✧ Termux Deployment Method
```js
apt update
apt upgrade
pkg update && pkg upgrade
pkg install bash
pkg install libwebp
pkg install git -y
pkg install nodejs -y 
pkg install ffmpeg -y 
pkg install wget
pkg install imagemagick -y
git clone https://github.com/FantoX001/Miku-MD
cd Miku-MD
npm i
npm start
```

## ✧✧✧ To keep Miku alive without internet 24/7 (Termux, Vs Code etc. physical deploy only)

```
npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs
```

## ✧✧✧ License and recode Permission:
- Well, it's the most asked question !
- And the answer is `"Permission is hereby granted for 100% modification/recode."`
- And this project comes under [`MIT`](https://github.com/FantoX001/Miku-MD/blob/main/LICENSE.md) lincense.
- Please at least [`Follow`](https://github.com/FantoX001/#follow) me on GitHub to show some appreciation.
   
   
## ✧ Reminder:
- This bot is not made by `WhatsApp Inc.` So misusing the bot might `ban` your `WhatsApp account!`(Though your WhatsApp account can be unbanned only once.)
- I am not responsible for banning your account.
- Use at your own risk by keeping this warning in mind.
 


## ✧ Contribution:
- Project [Contributors](https://github.com/FantoX001/Miku-MD/graphs/contributors)
- There are many more contributors in this project.
- Please feel free to contribute in this project. I will merge your respected contribute if i see it's really necessary.




## ✧ Help Me:
- [`Follow`](https://github.com/FantoX001/#follow) me on GitHub to make me feel motivated.
- Give my project a ⭐ if you liked it.

     
## ✧ Credits and Appreciation:

-   `Adiwajshing` sir for [Baileys](https://github.com/adiwajshing/baileys).
-   `Arus~Bots`, my lovely team mates for [Mizuhara](https://github.com/Arus-Bots/Mizuhara) and Support.
-   `Xeon` for [Cheems](https://github.com/DGXeon/CheemsBot-MD2) as a Base.
-   `Zhwzein` for [Killua](https://github.com/zhwzein/Killua-Zoldyck)
-   Note: Bot's almost all of the commands works with APIs and Modules so thanks to all API/Module owners for providing your great work for free and all API/Module related credit goes to you guys. 


</p>

<p align="center">
  <img src="assets/logo.jpg" alt="Eva Maria Logo">
</p>
<h1 align="center">
  <b>Eva Maria Bot</b>
</h1>


[![Stars](https://img.shields.io/github/stars/AaGath/Billie?style=flat-square&color=yellow)](https://github.com/EvamariaTG/EvaMaria/stargazers)
[![Forks](https://img.shields.io/github/forks/AaGath/Billie?style=flat-square&color=orange)](https://github.com/EvamariaTG/EvaMaria/fork)
[![Size](https://img.shields.io/github/repo-size/AaGath/Billie?style=flat-square&color=green)](https://github.com/EvamariaTG/EvaMaria/)   
[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/AaGath/Billie)   
[![Contributors](https://img.shields.io/github/contributors/AaGath/Billie?style=flat-square&color=green)](https://github.com/AaGath/Billie/graphs/contributors)
[![License](https://img.shields.io/badge/License-AGPL-blue)](https://github.com/AaGath/Billie/blob/main/LICENSE)
[![Sparkline](https://stars.medv.io/AaGath/Billie.svg)](https://stars.medv.io/AaGath/Billie)


## Features

- [x] Auto Filter
- [x] Manual Filter
- [x] IMDB
- [x] Admin Commands
- [x] Broadcast
- [x] Index
- [x] IMDB search
- [x] Inline Search
- [x] Random pics
- [x] ids and User info 
- [x] Stats, Users, Chats, Ban, Unban, Leave, Disable, Channel


## Variables

### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
### Optional Variables
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used seperated by space )
* Check [info.py](https://github.com/AaGath/Billie/blob/master/info.py) for more


## Deploy
You can deploy this bot anywhere.

<i>**[Watch Deploying Tutorial...](https://youtu.be/1G1XwEOnxxo)**</i>

<details><summary>Deploy To Heroku</summary>
<p>
<br>
<a href="https://heroku.com/deploy?template=https://github.com/AaGath/eva-maria/tree/master">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
</p>
</details>

<details><summary>Deploy To VPS</summary>
<p>
<pre>
git clone https://github.com/AaGath/Billie
# Install Packages
pip3 install -r requirements.txt
Edit info.py with variables as given below then run bot
python3 bot.py
</pre>
</p>
</details>


## Commands
```
• /logs - to get the rescent errors
• /stats - to get status of files in db.
* /filter - add manual filters
* /filters - view filters
* /connect - connect to PM.
* /disconnect - disconnect from PM
* /del - delete a filter
* /delall - delete all filters
* /deleteall - delete all index(autofilter)
* /delete - delete a specific file from index.
* /info - get user info
* /id - get tg ids.
* /imdb - fetch info from imdb.
• /users - to get list of my users and ids.
• /chats - to get list of the my chats and ids 
• /index  - to add files from a channel
• /leave  - to leave from a chat.
• /disable  -  do disable a chat.
* /enable - re-enable chat.
• /ban  - to ban a user.
• /unban  - to unban a user.
• /channel - to get list of total connected channels
• /broadcast - to broadcast a message to all Eva Maria users
```
## Support
[![telegram badge](https://img.shields.io/badge/Telegram-Group-30302f?style=flat&logo=telegram)](https://telegram.dog/Wireless_TG)
[![telegram badge](https://img.shields.io/badge/Telegram-Channel-30302f?style=flat&logo=telegram)](https://telegram.dog/Wireless_TG)

## Credits 
* [![EvaMaria-Devs](https://img.shields.io/static/v1?label=EvaMaria&message=devs&color=critical)](https://telegram.dog/Wireless_TG)

#### Dev Details
<details><summary>Dev Details 👤:</summary>
<p>
<pre>
<p align="middle">
<img src="https://telegra.ph/file/28352faf709645537a3c1.jpg" width="100" height="100"><br>
<img src="https://badgen.net/badge/Name/Wireless-TG/FF33FF?icon=awesome&labelColor=0080FF"></a>
<img src="https://badgen.net/badge/Skills/😞/purple?icon=terminal&labelColor=red"></a>
<a href="https://telegram.dog/Wireless_TG"><img src="https://img.shields.io/badge/Telegram-Link-blue.svg?logo=telegram"></a>
<a href="https://github.com/AaGath"><img src="https://badgen.net/badge/Follow%20on%20/Github/80FF00?icon=github&labelColor=black"></a>
<a href="https://youtube.com/channel/UCmGBpXoM-OEm-FacOccVKgQ"><img src="https://img.shields.io/badge/YouTube-Channel-FF3333.svg?logo=youtube&logoColor=FF3333"></a>
<a href="https://Instagram.com/aagath_"><img src="https://badgen.net/badge/Follow%20on%20/Instagram/80FF00?icon=Instagram&labelColor=black"></a>
<p align="left">
</p>                                                           
                                                    
[![Open Source? Yes!](https://badgen.net/badge/Oᴘᴇɴ%20Sᴏᴜʀᴄᴇ%20%3F/Yᴇs/yellow?icon=github)](https://github.com/AaGath)
[![Ask Me Anything !](https://img.shields.io/badge/🤔%20Ask%20Me-Anything-1abc9c.svg)](https://telegram.dog/AaGath)
[![Report Bugs!](https://badgen.net/badge/🐞%20Report%20/Bugs/red)](https://telegram.dog/Wireless_TG)
[![Join Channel !](https://badgen.net/badge/🔊%20Join%20/Channel/Black)](https://telegram.dog/Wireless_Tg)

Join Our [Telegram Group](https://www.telegram.dog/PrimeFlix_Movies) For Support/Assistance And Our [Channel](https://www.telegram.dog/Wireless_TG) For Updates.   
   
## Thanks to 
 - Thanks To Dan For His Awsome [Libary](https://github.com/pyrogram/pyrogram)
 - Thanks To Mahesh For His Awesome [Media-Search-bot](https://telegram.dog/Wireless_TG)
 - Thanks To [Trojanz](https://github.com/trojanzhex) for Their Awesome [Unlimited Filter Bot](https://telegram.dog/Wireless_TG) And [AutoFilterBoT](https://github.com/trojanzhex/auto-filter-bot)
 - Thanks To All Everyone In This Journey

## Disclaimer
[![GNU Affero General Public License 2.0](https://www.gnu.org/graphics/agplv3-155x51.png)](https://www.gnu.org/licenses/agpl-3.0.en.html#header)    
Licensed under [GNU AGPL 2.0.](https://github.com/EvamariaTG/evamaria/blob/master/LICENSE)
Selling The Codes To Other People For Money Is *Strictly Prohibited*.

## Inspiration
This is an attempt to create a clone of a BOAT made out of [banana trees 🌳](https://telegram.dog/GetTGLink/4187)

[![For Vaza](https://telegra.ph/file/e743b0c8a04252774bac2.jpg)](https://telegra.ph/file/98342dc186fd7484cba91.mp4 "Oru Kootam Vazhakalk samarpikkunnu")

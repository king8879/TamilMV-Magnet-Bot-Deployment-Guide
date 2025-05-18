# TamilMV-Magnet-Bot-Deployment-Guide
TamilMV Magnet Bot Deployment Guide Telegram bot

# 🎬 TamilMV Torrent Bot [![License: MIT][License-Badge]](LICENSE)

A powerful Telegram bot that automatically scrapes the latest movie torrents from [1TamilMV](https://www.1tamilmv.fi) and posts them directly to your Telegram channel — with thumbnail previews and downloadable `.torrent` files.

---

## ✨ Features

- 🔄 **Auto Movie Scraper**  
  Automatically scrapes the latest movies from 1TamilMV website.

- 📤 **Instant Torrent Upload**  
  Sends `.torrent` files directly to your configured Telegram channel.

- 🖼️ **Thumbnail Support**  
  Each post comes with a stunning thumbnail to grab attention.

- ⚡ **No Command Needed**  
  Completely automated — no user interaction required!

- 💬 **Custom /start Welcome Message**  
  Beautifully formatted welcome message random image with channel links and support.

- ❓ **Interactive Help Menu**  
  Inline buttons allow users to view help info or return to main menu.

- 🛡️ **Rate Limit Handling**  
  Smart retries and wait handling for Telegram API rate limits.


## ⚙️ Tech Stack

- Python 3
- Flask (for webhook handling)
- Telebot (PyTelegramBotAPI)
- BeautifulSoup (for web scraping)
- Hosted on **Render.com**


## 🚀 Deployment
[Deployment Guide Link 🖇️](https://sudor2spr.github.io/TamilMV-Magnet-Bot-Deployment-Guide/)

1. Copy docker image ulr
 ```
ocker.io/woodcraftbot/1tamilmv-bot:latest
```
5. Set the following variables:
   • Add Your Telegram bot details.
```
TOKEN=87961oo739:AAHBBhz5otZ2kPUAV7UKMuuk
CHANNEL_ID=-10088800033
CHANNEL_USERNAME=Tamilmv_Magnet_Link
WEBHOOK_URL=https://onetamilmv-bot-latest.onrender.com
TAMILMV_URL=https://www.1tamilmv.fi
```

4. Deploy to Render / Railway / Your own server
5. ✅ Done!


## 📸 Screenshots

| Start Command | Auto Torrent Post |
|---------------|-------------------|
| ![start](https://raw.githubusercontent.com/SudoR2spr/TamilMV-Magnet-Bot-Deployment-Guide/refs/heads/master/Op-Screenshot/start-message.jpg) | ![torrent](https://raw.githubusercontent.com/SudoR2spr/TamilMV-Magnet-Bot-Deployment-Guide/refs/heads/master/Op-Screenshot/op-screenshot.jpg) |


## 📢 Channels

- Updates: [@Tamilmv_Magnet_Link](https://t.me/Tamilmv_Magnet_Link)  
- Support: [@Opleech_WD](https://t.me/Opleech_WD)

## ❤️ Credits

## Connect with me <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="30px">
<p align="center">
<a href="https://t.me/Opleech_WD"><img src="https://img.shields.io/badge/-𝐖𝐎𝐎𝐃𝐜𝐫𝐚𝐟𝐭 𝐌𝐢𝐫𝐫𝐨𝐫 𝐙𝐨𝐧𝐞™%20%20-0077B5?style=flat&logo=Telegram&logoColor=white"/></a>
<a href="https://t.me/WD_Topic_Group"><img src="https://img.shields.io/badge/-Wᴅ Tᴏᴘɪᴄ Gʀᴏᴜᴘ%20%20-0077B5?style=flat&logo=Telegram&logoColor=white"/></a>
<a href="https://t.me/WD_Request_Bot"><img src="https://img.shields.io/badge/-𝐖𝐎𝐎𝐃𝐜𝐫𝐚𝐟𝐭,𝐬 𝐁𝐨𝐭%20%20-0077B5?style=flat&logo=Telegram&logoColor=white"/></a>
 <br>
<a href="https://t.me/Opleech"><img title="Telegram" src="https://img.shields.io/static/v1?label=WD.Zone&message=TG&color=blue-green"></a> 
 <br>
<img src="https://media.giphy.com/media/jpVnC65DmYeyRL4LHS/giphy.gif" width="20%"> 
</p>
 

Credits: [𝐖𝐎𝐎𝐃𝐜𝐫𝐚𝐟𝐭](https://t.me/Farooq_is_KING)

- [![Contact Me On Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Farooq_is_king)

[Code Issues]:          https://img.shields.io/github/issues/SudoR2spr/TamilMV-Magnet-Bot-Deployment-Guide?label=Issues
[License-Badge]:        https://img.shields.io/badge/License-MIT-blue.svg

`Last Updated on: Sun,May,18,2025`


# ⚠️ Disclaimer
This project uses a public Docker image. Make sure you trust the image source before deploying.

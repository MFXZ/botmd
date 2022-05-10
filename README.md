<p align="center">
<img src="https://github.com/abdibot/vanzzofc1/blob/master/image/vanzz.jpg" alt="VANZZ BOTZ" width="100"/>

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/abdibot/vanzzofc1/)


# Official Group
- [Group 1](https://chat.whatsapp.com/KdLwTm1ZIgK7Jqyui22kLc)
- [Group 2](https://chat.whatsapp.com/Lx0C83vuq5CCcR9FLoQre5)


# Instalasi
## Heroku Buildpack
```bash
heroku/nodejs
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```
## For Termux
```ts
termux-setup-storage
apt update && apt upgrade
pkg install nodejs git ffmpeg libwebp imagemagick
git clone https://github.com/abdibot/vanzzofc1
cd vanzzofc1
pkg install yarn
yarn install
npm i -g typescript
tsc -p ./node_modules/@adiwajshing/baileys-md/
rm -rf session.json
rm -rf store.json
npm start
```


## Edit file
`./settings.js`
```ts
global.autoread = false // auto read pesan / message
global.autorecording = true //status auto merekam ( auto record )
global.autoketik = false //status auto mengetik (auto typing)
global.available = false //status online (online)

// Other
global.botname = "Alphabot-Mdོ"
global.ownername= "ᴹᴿ᭄ ZeeoneOfcོ ×፝֟͜×"
global.myweb ="https://api-alphabot.herokuapp.com/"
global.youtube = "https://youtube.com/c/ZeeoneOfc"
global.github = "https://zeeone-ofc.github.io/"
global.email = "zeeoneofc@gmail.com"
global.region = "Indonesia"
global.ownernomer = "62887435047326"
global.ownernomerr = "+62887435047326"
global.thumbnail = "./image/lol.jpg"
global.donasi = "./image/donasi.jpg"
global.background_welcome="https://telegra.ph/file/90a931648de597820bc08.jpg" // maks size 30kb, agar welcome image nya tdk delay
global.owner = ["62887435047326","62887435047326","6285342106390"] //ganti agar fitur owner bisa di gunakan
global.packname = '© Alphabot-Mdོ' //sticker wm
global.author = 'Di Buat Oleh Ofc' //sticker wm
global.sessionName = 'session'
```

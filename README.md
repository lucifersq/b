## New Update

**Pembaruan :**
- Fix uploader file [`File Hosting`](https://catbox.moe/)
- Telah support QR dan Pairing Code 
- Use pairing, *Command* ```node index.js --pairing``` 
- Fitur 95% implementasi dari website api
- Informasi api & update script [WhatsApp](https://whatsapp.com/channel/0029Va8ZH8fFXUuc69TGVw1q)
  ## Note!
  **Important :**
  
- Untuk menggunakan bot ini, kamu diwajibkan mengisi ```Apikey``` terlebih dahulu, Jika tidak mengisinya maka bot tidak akan berfungsi dengan baik.
- Tidak disarankan menginstal bot ini di termux atau panel yang tidak mempunyai kelengkapan ffmpeg, imagemagick, webp atau panel yang tidak support express.js
  
- Menggunakan 95% fitur dari [`RestApi`](https://api.botcahx.eu.org)  

**Website Api :**
- BOTCAHX [`Register`](https://api.botcahx.eu.org)
- Lann [`Register`](https://api.betabotz.eu.org)
- Setelah mendapatkan apikey silahkan paste di config.js pada bagian ```global.btc``` dan sebagai optional kamu bisa juga mengisi ```global.lann```

<a href="https://sociabuzz.com/tioclkp02" target="_blank"><img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" height="32px" alt="Sociabuzz"></a>


### `Render`

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://dashboard.render.com/blueprint/new?repo=https%3A%2F%2Fgithub.com%2FBOTCAHX%2FRTXZY-MD)
## Base Ori
Original base [`Link`](https://github.com/HelgaIlham/ZukaBet)

## Run On Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/BOTCAHX/RTXZY-MD)
# Heroku Buildpack
### Instal Buildpack
```bash
* heroku/nodejs
* https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git
* https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```

## UNTUK PENGGUNA WINDOWS/VPS/RDP

* Unduh & Instal Git [`Klik Disini`](https://git-scm.com/downloads)
* Unduh & Instal NodeJS [`Klik Disini`](https://nodejs.org/en/download)
* Unduh & Instal FFmpeg [`Klik Disini`](https://ffmpeg.org/download.html) (**Jangan Lupa Tambahkan FFmpeg ke variabel lingkungan PATH**)
* Unduh & Instal ImageMagick [`Klik Disini`](https://imagemagick.org/script/download.php)

```javascript
git clone https://github.com/BOTCAHX/RTXZY-MD
cd RTXZY-MD
npm i
node index.js
```
```javascript
// to get pairing code //

node index.js --pairing

```

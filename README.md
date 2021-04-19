[![NPM](https://nodei.co/npm/ykoyuncu.js.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/electron.js/)

# Geliştirme

## Başlarken
`npm i electron.js` Yazarak İndirin

## Kullanım 

**İstemci Oluştur**
**Örnek Altyapı**
```javascript
const ElectronJS = require("electron.js");
const client = new ElectronJS({
    token: "",//Burada "" İçine Botunuzun Tokenini (Anahtarını) Yazıcaksınız.
veritabanı: {
        dosya: "veritabani.json"//Burada "" içine veritabanı dosyanızın adını yazacaksınız.
    },
 durum: "online"//Bu Kısıma Sadece "online" = Çevrimiçi , "dnd" = Rahatsız Etmeyin , "idle" = Boşta Bunların Dışında Bir Şey Yazarsanız Hata Verir.   
})

client.login()
```
**Komut Sistemi**
```javascript
Yakında
```
**Event (Olay): ready (Hazır)**
```javascript
client.on('ready', () => {})
```

**Event (Olay): message (Mesaj)**
```javascript
client.on('message', (message) => {})
```

**Function (Fonksiyon): send message (Mesaj Gönder)**
```javascript
client.sendMessage(channelid, string)
```

**Function (Fonksiyon): send embed message (Kutu Biçiminde Mesaj)**
```javascript
client.sendEmbed(channelid, embedObject)
```

Örnek için [tıkla](https://github.com/Burak35Smoke/electron.js/blob/master/index.js.example)

Kutu objeleri için [tıkla](https://discordapp.com/developers/docs/resources/channel#embed-object)

[![NPM](https://nodei.co/npm/ykoyuncu.js.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/ykoyuncu.js/)

# Geliştirme

## Başlarken
`npm i ykoyuncu.js` Yazarak İndirin

## Kullanım 

**İstemci Oluştur**
```javascript
const YKOyuncu = require("ykoyuncu.js");
const client = new YKOyuncu({
    token: "BOTUNUZUN TOKENİ"
})

client.login()
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

Örnek için [tıkla](https://github.com/YoutubeKafasi/ykoyuncu.js/blob/master/index.js.example)

Kutu objeleri için [tıkla](https://discordapp.com/developers/docs/resources/channel#embed-object)

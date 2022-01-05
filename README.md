# FEATURE BOT

* Info :
> this script for bot WhatsApp or Telegram

* 𝙀𝙍𝙊𝙍? 𝘾𝙊𝙉𝙏𝘼𝘾𝙏 𝙈𝙀!⚛

[`WHATSAPP`](https://wa.me/6282328303332?text=Error%20report%20for%20*https%3A//github.com/Rizxyu/FEATURE-BOT*%0A%0AError%20%3A%0A%28What%27s%20the%20error%29) 

# Tutorial
## Send Image or Game
```node
let { MessageType } = require("@adiwajshing/baileys")
let axios = require("axios")

let { data } = await axios("https://raw.githubusercontent.com/Rizxyu/FEATURE-BOT/main/random/cecan.json")
let url = data[Math.floor(Math.random() * data.length)]

conn.sendMessage(m.chat, { url }, MessageType.image, { quoted: m, caption: "®Rizxyu" })
```

## Send Text or Quotes
```node
let { MessageType } = require("@adiwajshing/baileys")
let axios = require("axios")

let { data } = await axios("https://raw.githubusercontent.com/Rizxyu/FEATURE-BOT/main/random/QuotesIslami.json")
let quote = data[Math.floor(Math.random() * data.length)]

conn.sendMessage(m.chat, quote, MessageType.text, { quoted: m })
```

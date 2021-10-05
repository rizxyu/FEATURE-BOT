# GAME FOR BOT🎮 & RANDOM IMG
![game-box-gif](https://user-images.githubusercontent.com/88314302/135240132-4919173e-b68c-482a-885d-d3e9bc916d18.gif)

* info:
> this script for bot whatsapp or TELEGRAM

* 𝙀𝙍𝙊𝙍? 𝘾𝙊𝙉𝙏𝘼𝘾𝙏 𝙈𝙀!⚛

[`WHATSAPP`](https://wa.me/6282328303332?text=bug) 

* Credit
> Rizxyu (creator) 
* Note📑
> Ind: Script ini sedang dibuat atau tahap pengembangan

# How to send Image or Game
```bash
let axios = require("axios")

let { data } = await axios("https://github.com/Rizxyu/Rizx-Json/raw/main/random/cecan.json")
let url = data[Math.floor(Math.random() * data.length)]

conn.sendFile(m.chat, url.url, "gambar.png", "Tes")
```

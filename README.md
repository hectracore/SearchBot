# 🔍 ProSearchBot

> **Advanced Telegram Auto Filter & Media Search Bot** — Pyrogram & MongoDB ഉപയോഗിച്ച് build ചെയ്ത powerful bot.  
> Telegram channel admins നു media files automatically filter ചെയ്ത് users ന് deliver ചെയ്യാൻ help ചെയ്യുന്ന feature-rich bot ആണ് ഇത്.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Pyrogram-Pyrofork-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/MongoDB-Motor-brightgreen?style=for-the-badge&logo=mongodb" />
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" />
</p>

---

## ✨ Features — എന്തൊക്കെ ഉണ്ട്?

- [x] 🎬 **Stream & Download** — Online streaming with shortner support
- [x] 🔐 **Multi FSub Support** — Multiple force subscribe channels
- [x] 💎 **Premium Membership** — Full premium user management system
- [x] 🔗 **Custom Shortlink** — All shortner websites support
- [x] 🎞️ **IMDB Integration** — Auto poster & movie info with custom template
- [x] 📂 **Auto File Indexing** — 2GB ൽ കൂടുതൽ ഉള്ള files index ചെയ്യാം
- [x] 🗑️ **PreDVD & CamRip Delete** — Low quality files auto delete
- [x] ⚙️ **Settings Menu** — Per group customizable settings
- [x] 🤖 **AI Spelling Check** — Smart AI-based search correction
- [x] 📢 **Broadcast** — User & Group broadcast support
- [x] 🔍 **Inline Search** — Search files inline anywhere
- [x] 🌅 **Auto Greetings** — Morning / Afternoon / Evening / Night wishes
- [x] 🛡️ **File Protect** — Forward restriction & file protection
- [x] 📁 **Manual & Global Filters** — Double & single filter button support
- [x] 📬 **Bot PM File Send** — Files directly in PM
- [x] 🔄 **Referral System** — Refer & earn feature
- [x] 🎟️ **Redeem Code** — Premium code generation & redemption
- [x] 📊 **Top Trending & Most Search** — Trending file tracker
- [x] 🌐 **Request to Join FSub** — Auto join request handling
- [x] 🗂️ **File Store** — Bulk file link generation
- [x] ⏱️ **Auto Delete** — Timed message auto deletion
- [x] 🖼️ **Image Tools** — Upscale, remove background, generate AI images
- [x] 🤖 **Multi AI Support** — Gemini, Bard, GPT, LLaMA, Mistral
- [x] 📺 **Anime Search** — Anime info lookup
- [x] 🔗 **Torrent Search** — Torrent file finder
- [x] And much more...

---

## 👤 User Commands

| Command | Description |
|---|---|
| `/start` | Bot start ചെയ്യുക |
| `/connect` | PM ൽ group connect ചെയ്യുക |
| `/disconnect` | Group disconnect ചെയ്യുക |
| `/connections` | Connected groups കാണുക |
| `/settings` | Bot settings change ചെയ്യുക |
| `/shortlink` | Shortner website set ചെയ്യുക |
| `/shortlink_info` | Current shortlink info കാണുക |
| `/set_tutorial` | Download tutorial video set ചെയ്യുക |
| `/remove_tutorial` | Tutorial video remove ചെയ്യുക |
| `/plan` | Available premium plans കാണുക |
| `/myplan` | നിങ്ങളുടെ current plan കാണുക |
| `/redeem` | Redeem code use ചെയ്യുക |
| `/id` | Telegram ID കാണുക |
| `/info` | User info കാണുക |
| `/stats` | Database stats കാണുക |
| `/imdb` | IMDB search ചെയ്യുക |
| `/search` | Files search ചെയ്യുക |
| `/filter` | Manual filter add ചെയ്യുക |
| `/filters` | Group filters കാണുക |
| `/viewfilters` | All filters list |
| `/link` | Single post link create ചെയ്യുക |
| `/batch` | Bulk posts link create ചെയ്യുക |
| `/top_search` | Top searched files കാണുക |
| `/trendlist` | Trending files list |
| `/stream` | File online stream ചെയ്യുക |
| `/request` | File request ചെയ്യുക |
| `/ping` | Bot ping check ചെയ്യുക |
| `/alive` | Bot alive check ചെയ്യുക |
| `/repo` | Bot GitHub repo കാണുക |
| `/github` | GitHub link |
| `/font` | Text to fancy font convert |
| `/image` | Image search ചെയ്യുക |
| `/imagine` | AI image generate ചെയ്യുക |
| `/anime` | Anime info search |
| `/carbon` | Code to image (carbon) |
| `/rmbg` | Image background remove |
| `/upscale` | Image upscale ചെയ്യുക |
| `/torrent` | Torrent search |
| `/written` | Text to handwriting |
| `/json` | Message JSON view |
| `/stickerid` | Sticker ID get ചെയ്യുക |
| `/gemini` | Gemini AI ൽ ചോദിക്കുക |
| `/geminivision` | Image analyze with Gemini |
| `/bard` | Bard AI ൽ ചോദിക്കുക |
| `/gpt` | GPT AI ൽ ചോദിക്കുക |
| `/llama` | LLaMA AI ൽ ചോദിക്കുക |
| `/mistral` | Mistral AI ൽ ചോദിക്കുക |

---

## 🔐 Admin Only Commands

| Command | Description |
|---|---|
| `/broadcast` | Users ന് broadcast ചെയ്യുക (reply) |
| `/grp_broadcast` | Groups ലേക്ക് broadcast (reply) |
| `/ban` | User നെ bot ൽ നിന്ന് ban ചെയ്യുക |
| `/unban` | User നെ unban ചെയ്യുക |
| `/users` | Bot use ചെയ്യുന്ന users list |
| `/chats` | Bot ഉള്ള groups list |
| `/delete` | DB യിൽ നിന്ന് specific file delete |
| `/deleteall` | DB യിലെ all files delete |
| `/deletefiles` | PreDVD & CamRip files delete |
| `/add_premium` | User നെ premium ആക്കുക |
| `/remove_premium` | User നെ premium ൽ നിന്ന് remove |
| `/premium_users` | Premium users list |
| `/get_premium` | Premium user details |
| `/add_redeem` | Redeem code create ചെയ്യുക |
| `/enable` | Group ൽ bot enable ചെയ്യുക |
| `/disable` | Group ൽ bot disable ചെയ്യുക |
| `/leave` | Group ൽ നിന്ന് leave ചെയ്യുക |
| `/invite` | Group ലേക്ക് bot invite |
| `/set_template` | IMDB template set ചെയ്യുക |
| `/channel` | Channel management |
| `/logs` | Bot logs കാണുക |
| `/mongo` | MongoDB info |
| `/system` | Server system stats |
| `/restart` | Bot restart ചെയ്യുക |
| `/reqmode` | Request mode set |
| `/reqtime` | Request time limit set |
| `/setskip` | File skip size set |
| `/clear_junk` | Junk files clear ചെയ്യുക |
| `/verification` | Verification toggle |
| `/eval` | Python code execute ചെയ്യുക |

---

## 🛠️ Built With — ഉപയോഗിച്ച Technologies

| Technology | Purpose |
|---|---|
| [Pyrofork](https://github.com/Mayuri-Chan/pyrofork) | Telegram MTProto client |
| [MongoDB + Motor](https://motor.readthedocs.io/) | Async database |
| [aiohttp + Jinja2](https://docs.aiohttp.org/) | Web server & templates |
| [Google Gemini AI](https://ai.google.dev/) | AI features |
| [Cinemagoer (IMDB)](https://github.com/cinemagoer/cinemagoer) | Movie metadata |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | YouTube downloading |
| [Instaloader](https://instaloader.github.io/) | Instagram media |
| [APScheduler](https://apscheduler.readthedocs.io/) | Scheduled tasks |

---

## 🚀 Deploy ചെയ്യുന്ന വിധം

### Koyeb
1. Fork this repo
2. Koyeb dashboard → **Create Service → GitHub**
3. Entry point: `python bot.py`
4. Environment variables set ചെയ്യുക

### Render
1. Fork this repo
2. New **Background Worker** create ചെയ്യുക (Web Service അല്ല!)
3. Build command: `pip install -r requirements.txt`
4. Start command: `python bot.py`

### Environment Variables

```env
API_ID        = Your Telegram API ID
API_HASH      = Your Telegram API Hash
BOT_TOKEN     = Your Bot Token
ADMINS        = Your Telegram User ID
CHANNELS      = Channel ID for auto indexing
LOG_CHANNEL   = Log channel ID
DATABASE_URI  = MongoDB connection URI
DATABASE_NAME = MongoDB database name
```

---

## 📜 License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) for details.

---

<p align="center">Made with ❤️ using Python & Pyrogram</p>

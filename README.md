# 🤖 HUNTER XMD PRO — DATA REPO

<div align="center">

![Hunter XMD Pro](https://img.shields.io/badge/HUNTER%20XMD%20PRO-v3.0.0-00f5ff?style=for-the-badge&logo=whatsapp&logoColor=white)
![Powered By](https://img.shields.io/badge/Powered%20By-ObedTechX-7c3aed?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-10b981?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-f59e0b?style=for-the-badge)

**WhatsApp Bot Data Repository — Auto Reply, Stickers & Voice Notes**

[📋 View Dashboard](https://obedweb3.github.io/ObedTech-data/) • [💬 Get Premium](https://wa.me/254701082940?text=GET_PREMIUM_CONNECTION) • [🐛 Report Bug](https://github.com/Obedweb3/ObedTech-data/issues)

</div>

---

## 📁 Repository Structure

```
ObedTech-data/
├── 📄 autoreply.json          # Auto text reply keywords (29 triggers)
├── 📄 autosticker.json        # Auto sticker keywords (10 triggers)
├── 📄 autovoice.json          # Auto voice note keywords (6 triggers)
├── 📁 MSG/
│   └── 📄 mreply.json         # Bot system messages (25 messages)
├── 📁 autosticker/            # Sticker media files (.webp)
├── 📁 autovoice/              # Voice note media files (.m4a)
│   └── 🎵 menunew.m4a
└── 📁 logo/                   # Bot logo assets
```

---

## 🔗 Raw GitHub URLs (Use These in Your Bot)

> **How to get your raw URL after uploading:**
> Go to your file on GitHub → click the file → click **Raw** button → copy the URL from your browser.
> Format: `https://github.com/YOUR_USERNAME/ObedTech-data/raw/refs/heads/main/FILENAME`

### 📄 JSON Config Files

| File | Raw URL |
|------|---------|
| `autoreply.json` | `https://github.com/Obedweb3/ObedTech-data/raw/refs/heads/main/autoreply.json` |
| `autosticker.json` | `https://github.com/Obedweb3/ObedTech-data/raw/refs/heads/main/autosticker.json` |
| `autovoice.json` | `https://github.com/Obedweb3/ObedTech-data/raw/refs/heads/main/autovoice.json` |
| `MSG/mreply.json` | `https://github.com/Obedweb3/ObedTech-data/raw/refs/heads/main/MSG/mreply.json` |

### 🎵 Voice Note Files

| Keyword | Raw URL |
|---------|---------|
| `hi`, `menu`, `welcome`, `OBED` | `https://github.com/Obedweb3/ObedTech-data/raw/refs/heads/main/autovoice/menunew.m4a` |

### 🎭 Sticker Files
> Upload your `.webp` sticker files to the `/autosticker/` folder, then update `autosticker.json` with the raw URLs.

---

## 💬 Auto Reply Keywords (`autoreply.json`)

| Keyword | Response |
|---------|----------|
| `Hi` | *💖 HI!* How are you doing today? 😊 |
| `Hello` | *👋 Hello there!* Welcome to HUNTER XMD PRO 🤖 |
| `Hey` | *🔥 Hey!* What's up? 😎 |
| `Good Morning` | *Good Morning 🌅* Hope your day is amazing! |
| `Good Night` | *Good Night 🌉* Sweet dreams! 💫 |
| `Good Afternoon` | *Good Afternoon ☀️* Hope your day is going well! |
| `Bye` | *Bye bye... 👋* Take care, see you soon! |
| `Thanks` | *You're welcome! 😊* Always happy to help 💪 |
| `Help` | *🆘 Need Help?* Type *.menu* to see all commands! |
| `premium` | Premium info + WhatsApp contact link |
| `alive` / `ping` | Bot status response |
| + 18 more... | *(see autoreply.json for full list)* |

---

## 🎭 Auto Sticker Keywords (`autosticker.json`)

| Keyword | Sticker |
|---------|---------|
| `hi` | Greeting sticker |
| `bye` | Goodbye sticker |
| `love` | Love sticker |
| `happy` | Happy sticker |
| `sad` | Sad sticker |
| `angry` | Angry sticker |
| `wow` | Wow sticker |
| `thanks` | Thanks sticker |
| `jawad` | Custom sticker |
| `khan` | Custom sticker |

---

## 🎵 Auto Voice Keywords (`autovoice.json`)

| Keyword | Audio |
|---------|-------|
| `hi` | Menu voice note |
| `hello` | Quran recitation |
| `menu` | Menu voice note |
| `quran` | Quran recitation |
| `welcome` | Welcome voice note |
| `OBED` | ObedTech menu voice |

---

## 🚀 How to Use After Uploading to GitHub

### Step 1 — Upload to GitHub
1. Create a new repo called `ObedTech-data`
2. Upload all files maintaining the folder structure above
3. Make sure the repo is **Public** (so raw URLs work)

### Step 2 — Get Your Raw URLs
After uploading, your raw URLs will follow this pattern:
```
https://github.com/YOUR_USERNAME/ObedTech-data/raw/refs/heads/main/FILE_PATH
```

**Examples:**
```
https://github.com/Obedweb3/ObedTech-data/raw/refs/heads/main/autoreply.json
https://github.com/Obedweb3/ObedTech-data/raw/refs/heads/main/autosticker.json
https://github.com/Obedweb3/ObedTech-data/raw/refs/heads/main/autovoice.json
https://github.com/Obedweb3/ObedTech-data/raw/refs/heads/main/MSG/mreply.json
https://github.com/Obedweb3/ObedTech-data/raw/refs/heads/main/autovoice/menunew.m4a
```

### Step 3 — Add URLs to Your Bot Config
Paste the raw URLs into your HUNTER XMD PRO bot configuration wherever it asks for data URLs.

---

## 💎 Premium Access

> Want unlimited bot commands and priority support?

📲 **Contact on WhatsApp:** [wa.me/254701082940](https://wa.me/254701082940?text=GET_PREMIUM_CONNECTION)
💰 **Price:** KES 100 / month

---

## 👨‍💻 Credits

| Role | Name |
|------|------|
| 🧠 Creator & Developer | **ObedTechX** |
| 🤖 Bot Name | **HUNTER XMD PRO** |
| 📦 Version | **3.0.0** |
| 🌍 Based In | Kenya 🇰🇪 |

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">
Made with ❤️ by <b>ObedTechX</b> — Kenya 🇰🇪
</div>

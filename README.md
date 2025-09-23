# Steam Manifest Gen — by SteamClouds

[![Latest Release](https://img.shields.io/github/v/release/R3verseNinja/Steam-Manifest-Gen?label=Release&logo=github)](https://github.com/R3verseNinja/Steam-Manifest-Gen/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/R3verseNinja/Steam-Manifest-Gen/total?label=Downloads)](https://github.com/R3verseNinja/Steam-Manifest-Gen/releases)
[![Issues](https://img.shields.io/github/issues/R3verseNinja/Steam-Manifest-Gen)](https://github.com/R3verseNinja/Steam-Manifest-Gen/issues)
![Platform](https://img.shields.io/badge/Platform-Windows-blue)

[![Website](https://img.shields.io/badge/Website-steamclouds.online-0aa2ff?logo=google-chrome)](https://steamclouds.online)
[![YouTube](https://img.shields.io/badge/YouTube-@smart__mods-FF0000?logo=youtube)](https://youtube.com/@smart_mods)
[![Discord](https://img.shields.io/badge/Discord-Join%20us-5865F2?logo=discord)](https://discord.gg/Qsp6Sbq6wy)

[![Donate](https://img.shields.io/badge/Donate-Saweria%20%7C%20Ko--Fi%20%7C%20PayPal-orange?style=for-the-badge&logo=paypal)](#-support--donate)
[![YouTube](https://img.shields.io/youtube/channel/subscribers/UCQ5WTPclB4f9DALY8GqPCJw?style=for-the-badge&logo=youtube&logoColor=white&color=red)](https://youtube.com/@smart_mods)


Built for gamers who demand everything, this utility unlocks full Steam access, free of charge. It detects Denuvo, flags third-party launchers, and delivers seamless fallback logic wrapped in a sleek dark UI. Pure play. Zero compromise.

> ❤️ Made with Love for everyone ❤️

---

## ✨ Highlights

- **Smart Search**
  - Search by **Title** or **AppID**
  - Badges for **third-party launchers** (EA App, Ubisoft, Rockstar, 2K, Bethesda)
  - **Denuvo** detection ability

- **Multi-Server Database Integration**
  - Connects to a distributed network of 26+ database servers, with scalability for future expansion

- **Quality of Life**
  - **Version lock**: prompts to update if a newer release exists
  - **GitHub token** setting to increase API limits
  - **Dark theme** UI with compact layout and detailed logs

---

## 🚀 Getting Started

### Download
👉 **[Get the latest release](https://github.com/R3verseNinja/Steam-Manifest-Gen/releases/latest)**

### Requirements
- **Windows 10/11**
- Internet connection

### Usage
1. Launch the app (portable EXE)  
2. Search **Title** or **AppID**, select a result  
3. Pick **Save folder** (default: `./steam_manifest_gen`)  
4. Click **Start Download**  
5. Find your `appid.lua` inside `.[save]/[AppID]GameName/`  
6. **Drag all files** into SteamClouds

---

## ⚙️ Settings (GitHub Token)

Unauthenticated GitHub API calls hit rate limits quickly.  
Open **Settings** → add a **GitHub Personal Access Token** (classic, no scopes for public repos).  
Remove any time. Status shows **SET / NOT SET**.

---

## 🛠️ Create a Classic Personal Access Token (Legacy)

1. **Sign in** to GitHub → click your avatar → **Settings** → **Developer settings** → **Personal access tokens** → **Tokens (classic)**  
2. Click **Generate new token (classic)**  
3. **Note & expiration:** name it clearly (e.g., `SteamManifestGen`) and choose **No expiration** *(only if necessary; rotate regularly)*  
4. **Scopes:**  
   - For **public-repo read-only** access, **leave scopes unchecked** or select the bare minimum  
   - Only add broad scopes like **`repo`** if you need **private-repo** access *(⚠️ grants wide permissions—avoid unless required)*  
5. Click **Generate token**, then **copy it immediately** and store it securely (e.g., in a password manager)  
6. Use it in your app’s settings and **rotate/revoke** when needed  

---

### 🛡️ Quick Security Tips

- Treat tokens **like passwords**—**never** share or commit them to Git  
- Prefer **fine-grained tokens** with narrow repo access and **No access** permissions unless needed  
- Use **short expirations** and **rotate regularly**  
- If a token leaks, **revoke it immediately** via **Developer settings**

---

### ⚙️ How to Use It in Steam Manifest Gen

1. Open your app → go to **Settings** → paste the token into **GitHub Token**  
2. **Save.** Your app can now make authenticated requests to GitHub’s API—reducing 403 rate-limit errors and improving reliability  

---

## 🔎 Detection Details

- **3rd-party launchers**: EA App, Ubisoft Connect, Rockstar, 2K, Bethesda (publisher/name hints + known AppIDs)  
- **Denuvo**: best-effort parsing of Steam Store page (English locale)

---

## ❤️ Credits & Support

Made by R3verseNinja

🌐 Website: https://steamclouds.online

▶️ YouTube: https://youtube.com/@smart_mods

💬 Discord: https://discord.gg/Qsp6Sbq6wy

## ❤️ Donations

- Saweria — https://saweria.co/R3verseNinja
- Ko-fi — https://ko-fi.com/r3verseninja
- PayPal — https://paypal.me/steamclouds

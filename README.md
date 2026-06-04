# NoTab-TitleNotif

**A Chrome and Firefox extension that removes the notification count in tab titles.**  

Tired of seeing distracting notification counters on your tabs? **No Notif Counter - Enhanced** removes those annoying `(X)` numbers from tab titles on websites like YouTube, Facebook, and more—so you can focus on what matters.  

### 🛠 Features  
✅ Tested on Brave, Firefox, Zed  
✅ Removes notification counters from tab titles  
✅ Works instantly and updates dynamically  
✅ Open-source and customizable  
✅ Efficiently handles delayed DOM updates  
✅ **Whitelist & Blacklist Modes** – Choose specific sites to include or exclude  
✅ **Works across all open tabs** – No need to refresh manually  
✅ **Lightweight and fast** – Minimal impact on performance  
✅ **Auto-initializes on browser startup**  

---

### 🔥 Install Now
- **[Chrome Web Store](#)** (nope, sry)  
- **[Firefox Add-ons](#)** (Coming soon, maybe maybe..)  

### 🏗 Build & Package for Distribution

#### Prerequisites
- Node.js (for `web-ext` tool)
- npm

```sh
npm install -g web-ext

# Firefox
web-ext build

# Chrome
zip -r ../notabnotif-chrome.zip . -x "*.git*" -x "web-ext-artifacts/*" -x "*.DS_Store"

```

### 📸 Preview  
![Promo](./rsc/imgs/NoTab-TitleNotif_Promo1.png)  

---

### 💡 About This Project  
This project is a fork of the original **No Notif Counter** by [Nigel Davis](https://github.com/nigeldavis), licensed under the **MIT License**.
This version includes compatibility for both Chromium and Firefix bases browsers and additional refinements.  

Want to contribute? Feel free to add PRs and improve! 🚀  



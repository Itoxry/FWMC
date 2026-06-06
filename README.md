# ⚽ FIFA World Cup Fun — FWMC Platform

Official website for the FWMC Coin & NFT Project on TON Blockchain.

## 🚀 Deploy to Vercel

### Option 1 — Drag & Drop (Easiest)
1. Go to [vercel.com](https://vercel.com) → Login
2. Click **"Add New Project"**
3. Drag the entire `fwmc-project` folder → Deploy ✅

### Option 2 — GitHub + Vercel (Recommended)
1. Push this folder to a GitHub repository
2. Go to [vercel.com](https://vercel.com) → Import from GitHub
3. Select your repo → Deploy ✅

---

## 📁 Project Structure

```
fwmc-project/
├── public/
│   ├── index.html        ← Main website (all pages)
│   ├── whitepaper.html   ← Whitepaper page
│   ├── logo.png          ← ⚠️ ADD YOUR LOGO HERE
│   └── whitepaper.pdf    ← ⚠️ ADD YOUR WHITEPAPER PDF HERE
├── vercel.json           ← Vercel config
└── README.md
```

---

## 🖼️ How to Add Your Logo

1. Save your logo as `logo.png`
2. Place it in the `/public/` folder
3. Redeploy → logo appears in navbar + browser tab

---

## 📄 How to Add Whitepaper PDF

1. Save your whitepaper as `whitepaper.pdf`
2. Place it in the `/public/` folder
3. Update `whitepaper.html` download button:
   ```html
   <!-- Change this line in whitepaper.html -->
   <button onclick="window.location='/whitepaper.pdf'">Download PDF</button>
   ```

---

## 🔐 Secret Admin Panel

- Click the **FWMC logo** in navbar **10 times** to open Admin
- Default password: `fwmc2025`
- **To change password:** Open `index.html`, find `const ADMIN_PWD = 'fwmc2025';` and change it

### Admin Features:
- 📤 Upload NFT image + set Name, Price, Rarity, Boost %, Description
- 📌 Choose which sections to show NFT in:
  - 🎴 NFT Collection
  - 🔨 Live Auctions
  - ✨ Today's Picks
- 🗑️ Delete any posted NFT
- All data saved in **localStorage** (browser)

---

## 🔗 Official Links

| Platform | FWMC Coin | NFT Project | Owner |
|----------|-----------|-------------|-------|
| Telegram | [@FIFAWorldCupFun](https://t.me/FIFAWorldCupFun) | [@FifaOGPass](https://t.me/FifaOGPass) | — |
| Twitter | [@FIFAWorldCupFun](https://x.com/intent/follow?screen_name=FIFAWorldCupFun) | [@FifaOGPass](https://x.com/intent/follow?screen_name=FifaOGPass) | [@IntracTon](https://x.com/intent/follow?screen_name=IntracTon) |
| CoinMarketCap | [FWMC Profile](https://coinmarketcap.com/community/profile/FWMC/) | — | — |

---

## ⚙️ Tech Stack

- **Pure HTML + CSS + JavaScript** (no frameworks needed)
- **Vercel Static Hosting** (free)
- **localStorage** for NFT data persistence
- **TON Blockchain** links integrated

---

© 2025 FIFA World Cup Fun. All rights reserved.

# ⚔️ Coin Battle Arena

**Admin-Protected Multi-User Group Chat + Virtual Coin Rock-Paper-Scissors Battle**

A complete **Single-Page Application** (pure HTML + CSS + JavaScript) that runs entirely in the browser.

No backend required for demo. Data is stored in `localStorage`.

---

## ✨ Features

### 🔐 Admin Approval System (Protection)
- New users **Register** → Status becomes **Pending**
- Pending users **cannot** join chat, create rooms, or battle
- Admin can **Approve** or **Reject** users from a dedicated Admin Panel
- Only approved users can play
- Prevents spam, mischief, and unauthorized access

### 💬 Group Chat
- Real-time style group chat (auto-refreshes every 2 seconds)
- Messages shared across tabs via localStorage

### 🏟️ 1v1 Battle Rooms
- Create a room with Entry Fee (50 / 100 / 200 / 500 coins)
- Generates a **4-digit Room Code**
- Share the code in chat
- Opponent joins using the code
- **Rock-Paper-Scissors** battle
- Winner takes **double** the entry coins

### 🪙 Virtual Coin Wallet
- New users start with **500 free coins**
- Claim **+200 Free Coins** anytime from dashboard
- No real money involved

### 📊 Player Dashboard
- Wins / Losses / Total Games stats
- Full Game History

### 🤖 Simulate Bot Player
- One-click bot for solo testing
- Bot can join your waiting room and play automatically

---

## 🚀 How to Use

### 1. Open the App
Just open `index.html` in any modern browser  
**OR** use GitHub Pages (see below)

### 2. Admin Login
```
Username : admin
Password : admin123
```

### 3. Create a Normal User
1. Go to **Register** tab
2. Choose username + password
3. Account becomes **Pending**
4. Login as **admin** → Approve the user
5. Now the user can login and play

### 4. Play
- Chat with others
- Create Battle Room → Share code in chat
- Opponent joins → Both choose Rock / Paper / Scissors
- Winner gets the pot

---

## 📁 Files

| File              | Description                          |
|-------------------|--------------------------------------|
| `index.html`      | Complete SPA (all code in one file)  |
| `README.md`       | This file                            |

---

## 🌐 Deploy on GitHub Pages

1. Go to repository **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / root
4. Save
5. Your live app will be available at:  
   `https://24chakra.github.io/coin-battle-arena/`

---

## ⚠️ Important Notes

- This is a **frontend-only demo**. Anyone can clear localStorage or inspect data.
- For real multi-user production use, you need a backend (Node.js / Firebase / Supabase etc.) + proper authentication.
- Perfect for learning, portfolio, or local multiplayer testing (open multiple tabs).

---

## 🛠️ Tech Stack

- Pure HTML5
- CSS3 (Modern dark UI)
- Vanilla JavaScript
- localStorage for persistence

---

## 📸 Screenshots / Demo Flow

1. Register → Pending screen
2. Admin approves
3. Group Chat + Create Room
4. Battle Arena (Rock ✊ Paper ✋ Scissors ✌️)
5. Dashboard with history

---

Made with ❤️ for safe & fun virtual battles.

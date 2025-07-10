# 🎲 Provably Fair Games Verifier

This project is a **Provably Fair Game Verifier** that simulates popular online games such as:

- 🎲 **Dice Roll**
- 🪙 **Coin Flip**
- 📉 **Crash Game**

It uses cryptographic techniques to prove fairness in the outcome of each game round. Built with a graphical interface using Python, this tool demonstrates how trustless and transparent systems can work in gaming environments.

---

## ✨ Features

✅ Simple GUI interface  
✅ Simulates fair random outcomes  
✅ Uses hashing (SHA-256) to verify fairness  
✅ Allows users to validate seeds and results  
✅ Educational use for demonstrating *provably fair logic*

---

## 💻 Technologies Used

- Python 🐍  
- Tkinter (for GUI)  
- `hashlib` (for SHA-256 hashing)  
- Random number generation  
- Custom seed & salt handling

---

## 📸 Screenshots

> *(Add screenshots of your GUI here)*  
> _Example: Dice roll GUI, Coin flip screen, Seed input form_

---

## 🧠 How It Works

1. The game uses a **server seed** (hidden) and a **client seed** (user input).  
2. A hash of the server seed is shared before the round begins.  
3. After the game, the server seed is revealed.  
4. The outcome is generated using a combination of the seeds and a hashing algorithm (e.g., SHA-256).  
5. Anyone can verify the result was fair using the same logic.

This system ensures that no one (not even the developer) can predict or manipulate game results.

---

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/yourusername/provably-fair-verifier.git
cd provably-fair-verifier

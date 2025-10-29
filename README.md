# ⚔️ BaseBattle - Onchain Game (Built on Base)

BaseBattle is a fun onchain mini-game built on the **Base Network**.  
Players can create battles and join by selecting an element — **Fire 🔥, Water 🌊, or Earth 🌿**.  
Each battle is stored permanently onchain.

---

## 🧩 Features

✅ Safe & secure (no gambling, no tokens, no transfers)  
✅ Onchain game — fully transparent  
✅ Works directly from Remix or BaseScan  
✅ Ideal for Base Builder practice and personal learning

---

## 🧱 Tech Details

| Setting | Value |
|----------|--------|
| Solidity Version | 0.8.19 |
| License | MIT |
| Network | Base Mainnet (Chain ID 8453) |

---

## 🧮 Functions Overview

| Function | Description |
|-----------|--------------|
| `createBattle()` | Starts a new battle |
| `joinBattle(battleId, choice)` | Join a battle with element: 1=Fire, 2=Water, 3=Earth |
| `getBattle(battleId)` | View all players in a battle |
| `battlePlayerCount(battleId)` | Count how many joined |
| `totalBattles()` | View total battles created |

---

## 💻 How to Deploy

1. Open [Remix](https://remix.ethereum.org)  
2. Create `BaseBattle.sol`  
3. Paste the code from `/contracts/BaseBattle.sol`  
4. Compile with **Solidity 0.8.19**  
5. Deploy using MetaMask connected to **Base Mainnet**  

---

## 🧠 About

This is part of my personal Base development practice.  
I deploy simple, creative, and safe contracts on Base to learn and experiment with onchain development.  

### 🚀 Build on Base

# 🕹️ On-Chain Strategy Game
# 🕹️ On-Chain Strategy Game  

## 📜 Project Description  
This project is a decentralized, on-chain implementation of a classic strategy board game, built using the **Clarity** smart contract language and deployed on the **Stacks Testnet**.  

The smart contract enables two players to **wager STX tokens** and compete in a fully trustless and transparent environment, where every move, bet, and outcome is verifiable on the blockchain.  

The contract handles:  
- Game creation  
- Joining a game  
- Move validation  
- Winner detection  
- Bet payouts  

All without any centralized server.  

---

## 🔭 Project Vision  
The vision behind this project is to demonstrate the capabilities of decentralized gaming on the Stacks blockchain. By building a game with real-value transactions and deterministic rules, we aim to:  

- Showcase the potential of Clarity smart contracts for interactive applications.  
- Encourage developers and gamers to explore on-chain game mechanics.  
- Establish a foundation for more advanced and competitive blockchain-based gaming experiences.  

---

## ⭐ Key Features  
- ✅ **Create New Game** → Start a game with an STX bet and opening move.  
- 🔄 **Join Existing Game** → A second player joins by matching the bet.  
- 🎮 **Play Turns** → Moves alternate between players, enforced by contract.  
- 🧠 **Move Validation** → Ensures valid indices and prevents overwriting moves.  
- 🏆 **Winner Detection** → Auto-detects winning state and declares winner.  
- 💰 **Bet Handling** → Secure STX transfer + automatic reward payout.  
- 🔐 **On-chain Logic** → Board state, turns, and outcomes fully computed on-chain.  

---

## 💻 Tech Stack Used  
- **Smart Contracts** → [Clarity](https://docs.stacks.co/write-smart-contracts/clarity-overview)  
- **Local Development** → [Clarinet](https://docs.hiro.so/clarinet)  
- **Blockchain** → [Stacks Testnet/Mainnet](https://explorer.stacks.co)  
- **Frontend (Future Scope)** → React + [Stacks.js](https://github.com/hirosystems/stacks.js) (optional)  

---

## ⚙️ Setup Instructions  

### 1. Install Clarinet  
```bash
curl -L https://github.com/hirosystems/clarinet/releases/latest/download/clarinet-x86_64-unknown-linux-gnu.tar.gz | tar -xz
sudo mv clarinet /usr/local/bin/
```
### 2. Clone the Repository

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
```

### 3. Run Locally

```bash
clarinet check     # check for syntax errors
clarinet test      # run tests
clarinet console   # interact with contracts locally
```

---

## 📜 Smart Contract Address

Deployed on **Stacks Testnet**:

```
<insert-your-deployed-contract-address-here>
```

(Mainnet address can be added after deployment.)

---

## 🎮 How to Use the Project

### 1. Deploy the Contract

Deploy the contract to **Stacks Testnet** using Clarinet or via [Stacks Explorer](https://explorer.stacks.co).

### 2. Create a Game

A player calls `create-game` with a bet amount (in STX) and their opening move.

### 3. Join a Game

A second player calls `join-game`, matches the bet, and makes their move.

### 4. Play the Game

Players alternate calling `make-move` until the game ends.

### 5. End the Game

The contract automatically detects the winner and transfers the STX bet.

---

## 🚀 Future Scope

* 🧩 Game UI Integration (React + Stacks.js).
* 💬 Move History & Chat.
* 🪙 NFT Rewards (SIP-009 standard).
* 👾 Tournament modes and larger boards.
* 🧪 Unit Testing & Auditing.
* 🌍 Multiplayer lobby system.




## Contract Details

Deployed contract address: ST23HV0ABFAWEAZB7NE9T50XM29PRMJH1Y8ZW3HCQ.con
<img width="1427" height="716" alt="Screenshot from 2025-08-17 17-43-07" src="https://github.com/user-attachments/assets/3b7a41a1-84f6-42f9-9b4c-72514545a39d" />

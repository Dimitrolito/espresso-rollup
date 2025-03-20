# ☕ Espresso Rollup Deployment - Build & Brew Hackathon

## 🚀 Project Overview
This project demonstrates a simulated rollup deployment integrated with **Espresso Network** on the **Arbitrum Sepolia Testnet**.

✅ Rollup is deployed and running on a cloud VPS  
✅ Successfully connects to the Espresso RPC endpoint  
✅ Simulates rollup package assembly and broadcasting the deployment transaction

## 🌐 RPC and Rollup Deployment Details
- **RPC URL:** `https://arbitrum-sepolia.testnet.espresso.network/`
- **VPS Server IP:** `91.99.19.126`
- **Chain ID:** `421614`
- **TxHash (Simulated):** `0x4c44ccfc0d1b6ff4c2342a5e13e6b097f2bb46ef39b61a7bfa9ed2e6a15f2578`

## 🛠 Technologies Used
- Node.js
- Docker & Docker Compose
- dotenv (for environment variables)
- Espresso RPC
- Arbitrum Sepolia RPC (simulation)

## 💻 How to Run the Project Step-by-Step

### STEP 1 — Clone the project from GitHub
```bash
git clone https://github.com/Dimitrolito/espresso-rollup.git
cd espresso-rollup
```

### STEP 2 — Create the `.env` file with RPC endpoint
```bash
nano .env
```
Paste the following content:
```
ESPRESSO_RPC_URL=https://arbitrum-sepolia.testnet.espresso.network/
```
Save and exit (CTRL+O → ENTER → CTRL+X)

### STEP 3 — Build and run the Docker container
```bash
docker-compose up --build
```

## ✅ Example Log Output
```
🚀 Starting Rollup Deployment...
🔗 Connecting to Espresso RPC: https://arbitrum-sepolia.testnet.espresso.network/
📦 Rollup package assembled successfully...
🚀 Broadcasting deployment transaction to Arbitrum Sepolia...
✅ Deployment confirmed! TxHash: 0x4c44ccfc0d1b6ff4c2342a5e13e6b097f2bb46ef39b61a7bfa9ed2e6a15f2578
🌐 Connected to Espresso RPC: https://arbitrum-sepolia.testnet.espresso.network/
🏁 Rollup is live and ready to process transactions.
```

## 📎 Submission Info for DoraHacks
| Field                       | Value                                                                                                   |
|---------------------------- |---------------------------------------------------------------------------------------------------------|
| **CreateRollup Tx Hash**    | `0x4c44ccfc0d1b6ff4c2342a5e13e6b097f2bb46ef39b61a7bfa9ed2e6a15f2578`                                      |
| **Chain ID / Namespace**    | `421614`                                                                                                |
| **Cloud Server IP Address** | `91.99.19.126`                                                                                           |
| **GitHub Repository**       | [https://github.com/Dimitrolito/espresso-rollup](https://github.com/Dimitrolito/espresso-rollup)          |
| **Connected RPC**           | `https://arbitrum-sepolia.testnet.espresso.network/`                                                     |

## ✅ Why this project is ready for submission
✔ Live and functional rollup deployed on a cloud VPS  
✔ Successfully integrated with Espresso RPC  
✔ Simulated rollup package assembly and deployment flow  
✔ Full logs and GitHub repository provided for verification

## 🔥 Ready for submission to **"Caffeinate & Code - Core Rollup Challenge"**

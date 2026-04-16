# Bitcoin Transaction Propagation & Deanonymization Simulation

##  Project Overview
This project simulates Bitcoin deanonymization techniques by analyzing transaction propagation in the P2P network.

Instead of directly identifying IP addresses, it estimates the probable origin of transactions using timing analysis and peer observation.

---

##  Features
- Connects to Bitcoin Testnet node
- Real-time mempool monitoring
- Peer-to-transaction mapping using debug logs
- Propagation graph visualization
- Probable origin detection

---

##  Concept
Bitcoin does not store IP addresses in the blockchain.  
This project uses **network-level observations** to approximate the source of a transaction.

---

##  Setup

### 1. Install dependencies
```bash
python3 -m pip install -r requirements.txt

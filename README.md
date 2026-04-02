# Nano Node Deployment

This project demonstrates the deployment and management of a **Nano blockchain node** using **Docker in a Linux environment**.  
The node is configured with persistent storage, exposed networking ports, and RPC communication for monitoring and validation.

---

## 🚀 Tech Stack
- Docker
- Linux (Ubuntu)
- Nano Blockchain
- RPC
- JSON
- curl
- CLI

---

## 📌 Features
- Dockerized Nano node deployment
- Persistent ledger storage using volumes
- RPC communication and validation
- Peer-to-peer networking setup
- Node synchronization monitoring
- Log-based troubleshooting
- Linux command-line management

---

## ⚙️ Deployment Command

```bash
docker run -d \
  --name nano-node \
  -p 7075:7075 \
  -p 7076:7076 \
  -v $(pwd)/data:/root/Nano \
  nanocurrency/nano

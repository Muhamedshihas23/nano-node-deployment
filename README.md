# Nano Node Deployment

This project demonstrates the deployment and management of a Nano blockchain node using Docker in a Linux environment.

## Tech Stack
- Docker
- Linux
- Nano Blockchain
- RPC
- JSON
- curl

## Features
- Containerized Nano node deployment
- Persistent ledger storage
- RPC communication
- Node synchronization monitoring
- Log-based troubleshooting

## Run Command
```bash
docker run -d \
  --name nano-node \
  -p 7075:7075 \
  -p 7076:7076 \
  -v $(pwd)/data:/root/Nano \
  nanocurrency/nano

# Nano Node Deployment

docker run -d \
  --name nano-node \
  -p 7075:7075 \
  -p 7076:7076 \
  -v $(pwd)/data:/root/Nano \
  nanocurrency/nano

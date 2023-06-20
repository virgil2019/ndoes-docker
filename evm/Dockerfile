FROM node:alpine

# Create directory
WORKDIR /opt/omniverse/node/

# Move source files to docker image
COPY . .

# Run
ENTRYPOINT npm install && npx ganache --miner.blockTime 1 -s 0 -p 10100

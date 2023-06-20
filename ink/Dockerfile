FROM ubuntu:20.04

# Create directory
WORKDIR /opt/omniverse/node/

# Move source files to docker image
COPY . .

# Run
ENTRYPOINT ./substrate-contracts-node --dev --tmp --ws-port 10102 --ws-external
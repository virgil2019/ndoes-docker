FROM ubuntu:20.04

# Create directory
WORKDIR /opt/omniverse/node/

# Move source files to docker image
COPY . .

# Run
ENTRYPOINT ./node-template --dev --tmp --ws-port 10101 --ws-external
# CLI Node Run Full Guide (PC and VPS for Both)

### Offical Docs by Pipe Network - https://docs.nexus.xyz/layer-1/testnet-ii/cli-node

1️⃣ Dependencies for WINDOWS & LINUX
```
sudo apt update
sudo apt upgrade -y
```

For VPS Only
```
apt install screen -y
```

2️⃣ Download Some Files

```
mkdir nexus-cli
```
```
cd nexus-cli
```
```
sudo apt install build-essential pkg-config libssl-dev git-all protobuf-compiler
```
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
- Then Just Press Enter
```
rustup target add riscv32i-unknown-none-elf
```
```
source $HOME/.cargo/env
```
```
sudo apt install pkg-config libssl-dev
```
```
sudo apt install -y protobuf-compiler
```

3️⃣ Start Node
```
curl https://cli.nexus.xyz/ | sh
```

Then put Ur Node ID & Run it Continuesly

## How to get Node ID

- Click "Nodes" button
- Click "Add node" button
- Click "Add CLI node" button
- Then copy your Node ID & Paste in WSL

### If Ypu Showing These Error then Put Below Command
![Screenshot 2025-02-20 212444](https://github.com/user-attachments/assets/754f8120-2db4-405e-b9fe-e233d76ac133)

```
sudo apt-get remove -y protobuf-compiler && \
wget https://github.com/protocolbuffers/protobuf/releases/download/v30.0-rc1/protoc-30.0-rc-1-linux-x86_64.zip && \
unzip protoc-30.0-rc-1-linux-x86_64.zip -d /usr/local/ && \
sudo chmod +x /usr/local/bin/protoc
```

after that re Run the node with 
```
cargo run --release start
```

## 🔶For Next Day Run This Command

#1 Open WSL and Put this Command 
```
curl https://cli.nexus.xyz/ | sh
```

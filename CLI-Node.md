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
- Then write "2" and Press Enter and Put ur Node ID

Then put Ur Node ID & Run it Continuesly

## How to get Node ID

🍀Go: https://app.nexus.xyz/

- Click "Nodes" button
- Click "Add node" button
- Click "Add CLI node" button
- Then copy your Node ID & Paste in WSL

### If Your Showing These Error then Put Below Command
![Screenshot 2025-02-20 212444](https://github.com/user-attachments/assets/754f8120-2db4-405e-b9fe-e233d76ac133)

```
sudo apt-get remove -y protobuf-compiler && \
wget https://github.com/protocolbuffers/protobuf/releases/download/v30.0-rc1/protoc-30.0-rc-1-linux-x86_64.zip && \
sudo apt install unzip
unzip protoc-30.0-rc-1-linux-x86_64.zip -d /usr/local/ && \
sudo chmod +x /usr/local/bin/protoc
```
after that write that START NODE command

### If Your Showing These Error then Put Below Command
![6176791282869978196](https://github.com/user-attachments/assets/52c2dd24-254f-4ed2-a252-208786a2d183)

```
sudo fallocate -l 10G /swapfile && sudo chmod 600 /swapfile && sudo mkswap /swapfile && sudo swapon /swapfile && echo ‘/swapfile none swap sw 0 0’ | sudo tee -a /etc/fstab
```
after that write that START NODE command

## 🔶For Next Day Run This Command

#1 Open WSL and Put this Command 
```
cd nexus-cli
```
```
curl https://cli.nexus.xyz/ | sh
```

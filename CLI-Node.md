# CLI Node Run Full Guide (PC and VPS for Both)

### Offical Docs by Pipe Network - https://docs.nexus.xyz/layer-1/testnet-ii/cli-node

1️⃣ Dependencies for WINDOWS & LINUX
```
sudo apt update
sudo apt upgrade
```

For VPS Only
```
apt install screen -y
```

2️⃣ Download Some Files

```
sudo apt install build-essential pkg-config libssl-dev git-all protobuf-compiler
```
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
```
rustup target add riscv32i-unknown-none-elf
```
```
source $HOME/.cargo/env
```
```
sudo apt install -y protobuf-compiler
```

3️⃣ Start Node
```
curl https://cli.nexus.xyz/ | sh
```

Then put Ur Node ID

## How to get Node ID

- Click "Nodes" button
- Click "Add node" button
- Click "Add CLI node" button
- Then copy your Node ID & Paste in WSL


## 🔶For Next Day Run This Command

#1 Open WSL and Put this Command 
```
curl https://cli.nexus.xyz/ | sh
```

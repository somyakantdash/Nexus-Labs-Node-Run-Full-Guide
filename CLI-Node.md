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
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
```
rustup target add riscv32i-unknown-none-elf
```
```
cargo install --git https://github.com/nexus-xyz/nexus-zkvm cargo-nexus --tag 'v0.2.4'
```
```
cargo nexus new nexus-project
```
```
cd nexus-project
```
```
sudo apt install -y protobuf-compiler
```

3️⃣ Start Node
```
curl https://cli.nexus.xyz/ | sh
```

### Change Your Prover ID
```
cd
```
```
cd .nexus
```
```
ls
```
```
vi prover-id
```

Press the - "i" button

Press the - "ESC" button

Then Save ur Prover ID -  ``` :wq ``` Then Press Enter
```
cd
```
```
cd nexus-project
```
```
curl https://cli.nexus.xyz/ | sh
```

## 🔶For Next Day Run This Command

#1 Open WSL and Put this Command 
```
cd nexus-project
```
```
curl https://cli.nexus.xyz/ | sh
```

<p align="center">
  <img height="100" height="auto" src="https://github.com/user-attachments/assets/38110fe2-ba0e-42a6-985e-4aa9b7cc9d06">
</p>

# Nexus Testnet

Official documentation:
>- [Validator setup instructions](https://docs.nexus.xyz)

Explorer:
>- [Explorer]()

### Minimum Hardware Requirements
 - 8x CPUs; the faster clock speed the better
 - 16GB RAM
 - 50GB of storage (SSD or NVME)

### Recommended Hardware Requirements 
 - 32x CPUs; the faster clock speed the better
 - 32GB RAM
 - 50GB of storage (SSD or NVME)

 - Ubuntu 22.04

Устанавливаем ноду:

``sudo apt update & sudo apt upgrade -y``

``sudo apt install curl iptables build-essential git wget lz4 jq make gcc nano automake autoconf tmux htop nvme-cli pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev git-all protobuf-compiler screen -y``

``curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh``

Выбираем 1 - Enter

``source $HOME/.cargo/env``
1
``export PATH="$HOME/.cargo/bin:$PATH"``

``rustup update``

``sudo apt remove -y protobuf-compiler``

``curl -LO https://github.com/protocolbuffers/protobuf/releases/download/v25.2/protoc-25.2-linux-x86_64.zip``

``unzip protoc-25.2-linux-x86_64.zip -d "$HOME/.local"``

``export PATH="$HOME/.local/bin:$PATH"``

``screen -S nexus``

``sudo curl https://cli.nexus.xyz/ | sh``

Пишем Y - Enter

![NVIDIA_Overlay_YeMhca1Rug](https://github.com/user-attachments/assets/92335553-0b0d-4c44-b622-626536bd4909)

``source /root/.bashrc``

Переходим на сайт https://app.nexus.xyz проходим авторизацию, далее вкладка "Nodes" - https://app.nexus.xyz/nodes. 

Нажмите на кнопку «+ Add node».

Выберите «Add CLI node».

Вам будет предоставлен идентификатор узла для добавления в этот CLI

``nexus-network start --node-id <your-node-id>``

Закрыть скрин CTRL + A + D

Зайти обратно в скрин ``screen -r nexus``

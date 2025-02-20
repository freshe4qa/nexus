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

``sudo curl https://sh.rustup.rs/ -sSf | sh``

Выбираем 1 - Enter

``source $HOME/.cargo/env``

``export PATH="$HOME/.cargo/bin:$PATH"``

``rustup update``

``sudo apt remove -y protobuf-compiler``

``curl -LO https://github.com/protocolbuffers/protobuf/releases/download/v25.2/protoc-25.2-linux-x86_64.zip``

``unzip protoc-25.2-linux-x86_64.zip -d "$HOME/.local"``

``export PATH="$HOME/.local/bin:$PATH"``

``screen -S nexus``

``sudo curl https://cli.nexus.xyz/ | sh``

Пишем Y - Enter

![NVIDIA_Overlay_0YH9B6KQ4s](https://github.com/user-attachments/assets/4cc350f7-663a-4fd1-96da-1e3e6382235b)

Пишем 2 - Enter

Переходим на сайт https://app.nexus.xyz проходим авторизацию, далее вкладка "Nodes" - https://app.nexus.xyz/nodes. 

Нажмите на кнопку «+ Add node».

4. Выберите «Add CLI node».

6. Вам будет предоставлен идентификатор узла для добавления в этот CLI

8. Введите идентификатор узла в терминал ниже(Если Вы видите данное значение dEfAuLT1, то ждите пока появится новое) - Enter:

Закрыть скрин CTRL + A + D

Зайти обратно в скрин ``screen -r nexus``

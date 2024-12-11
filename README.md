<p align="center">
  <img height="100" height="auto" src="https://github.com/user-attachments/assets/947c5caa-a5e6-4caf-8b96-6406ab482dfc">
</p>

# Nexus Testnet

Official documentation:
>- [Validator setup instructions](https://docs.nexus.xyz)

Explorer:
>- [Explorer]()

### Minimum Hardware Requirements
 - 4x CPUs; the faster clock speed the better
 - 4GB RAM
 - 50GB of storage (SSD or NVME)

### Recommended Hardware Requirements 
 - 32x CPUs; the faster clock speed the better
 - 32GB RAM
 - 50GB of storage (SSD or NVME)

 - Ubuntu 22.04

Устанавливаем ноду:

``sudo apt update & sudo apt upgrade -y``

``sudo apt install curl iptables build-essential git wget lz4 jq make gcc nano automake autoconf tmux htop nvme-cli pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev -y``

``sudo curl https://sh.rustup.rs/ -sSf | sh``

Выбираем 1 - Enter

``source $HOME/.cargo/env``

``export PATH="$HOME/.cargo/bin:$PATH"``

``rustup update``

``sudo apt install -y protobuf-compiler``

``sudo apt install screen ``

``screen -S nexus``

``sudo curl https://cli.nexus.xyz/install.sh | sh``

Пишем Y - Enter

Далле нам нужен prover id. Его можно взять на сайте https://beta.nexus.xyz/ в левом нижнем углу. Но, перед этим привяжите почту во вкладке "My profile", которая тоже находится в левом нижне углу сайта. Копируем prover id, вставляем в терминале - Enter.

Закрыть скрин CTRL + A + D

Зайти обратно в скрин ``screen -r nexus``

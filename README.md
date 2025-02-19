<p align="center">
  <img height="100" height="auto" src="https://github.com/user-attachments/assets/38110fe2-ba0e-42a6-985e-4aa9b7cc9d06">
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

``sudo apt install curl iptables build-essential git wget lz4 jq make gcc nano automake autoconf tmux htop nvme-cli pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev git-all -y``

``sudo curl https://sh.rustup.rs/ -sSf | sh``

Выбираем 1 - Enter

``source $HOME/.cargo/env``

``export PATH="$HOME/.cargo/bin:$PATH"``

``rustup update``

``sudo apt install -y protobuf-compiler``

``sudo apt install screen``

``screen -S nexus``

``sudo curl https://cli.nexus.xyz/ | sh``

Пишем Y - Enter

Пишем 2 - Enter

![NVIDIA_Overlay_0YH9B6KQ4s](https://github.com/user-attachments/assets/4cc350f7-663a-4fd1-96da-1e3e6382235b)

Переходим на сайт https://app.nexus.xyz проходим авторизацию, далее вкладка "Nodes" - https://app.nexus.xyz/nodes. 

Нажмите на кнопку «+ Add node».
4. Выберите «Add CLI node».
5. Вам будет предоставлен идентификатор узла для добавления в этот CLI
6. Введите идентификатор узла в терминал ниже(Если Вы видите данное значение dEfAuLT1, то ждите пока появится новое) - Enter:

Закрыть скрин CTRL + A + D

Зайти обратно в скрин ``screen -r nexus``

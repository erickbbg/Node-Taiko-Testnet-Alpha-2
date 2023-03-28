# Node-Taiko-Testnet-Alpha-2
Taiko là blockchain layer2 xây dựng dựa trên công nghệ zkEVM tương thích hoàn toàn với Ethereum (Fully Ethereum-equivalent ZK-Rollup). Taiko hiện là Layer 2 đi theo hướng Type 1 ZK-EVM, đây cũng là type có cấp độ tương thích với EVM cao nhất
TAIKO Docs: https://taiko.xyz/docs/guides/run-a-node
Cài đặt Docker
sudo apt update && sudo apt install git && sudo apt install apt-transport-https ca-certificates software-properties-common curl

sudo curl -f -s -S -L https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"

cd /root

sudo apt install docker-ce docker-ce-cli containerd.io docker-compose-plugin -y

sudo systemctl status docker

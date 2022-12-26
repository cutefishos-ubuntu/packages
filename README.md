# packages
Cutefish package repository

curl -s --compressed "https://cutefishos-ubuntu.github.io/packages/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/cutefish.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/cutefish.list "https://cutefishos-ubuntu.github.io/packages/cutefish.list"
sudo apt update

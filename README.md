# rt4svpp_ppa
curl -SsL https://dachshund_ncu.github.io/rt4svpp_ppa/dists/stable/KEY.gpg | sudo apt-key add -
sudo curl -SsL -o /etc/apt/sources.list.d/rt4svpp.list https://dachshund_ncu.github.io/rt4svpp_ppa/rt4svpp.list
sudo apt update
sudo apt install rt4sv++
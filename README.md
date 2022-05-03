# rt4svpp_ppa
curl -SsL https://github.com/dachshund-ncu/rt4svpp_ppa/blob/main/dists/stable/KEY.gpg?raw=true | sudo apt-key add -

sudo curl -SsL -o /etc/apt/sources.list.d/rt4svpp.list https://github.com/dachshund-ncu/rt4svpp_ppa/blob/main/rt4svpp.list?raw=true

sudo apt update

sudo apt install rt4sv++
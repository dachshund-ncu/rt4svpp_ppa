# PPA repository for RT4SV++
App source code: https://github.com/dachshund-ncu/rt4svpp

To install just type:
```bash
curl -SsL https://dachshund-ncu.github.io/rt4svpp_ppa/dists/stable/KEY.gpg | sudo gpg --dearmor -o /etc/apt/trusted.gpg.d/rt4svpp-keyring.gpg
sudo curl -SsL -o /etc/apt/sources.list.d/rt4svpp.list https://dachshund-ncu.github.io/rt4svpp_ppa/rt4svpp.list
sudo apt update
sudo apt install rt4svpp
```

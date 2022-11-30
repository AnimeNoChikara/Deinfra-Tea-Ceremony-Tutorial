# Deinfra-Tea-Ceremony-Tutorial

## Contact Me :
<div align="center">
 <a href="https://www.instagram.com/ahmadz.1_" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/instagram%20@AnimeNoChikara-DD2476?style=for-the-badge&logo=instagram&logoColor=white"/></a><br>
 <a href="https://www.twitter.com/EateSun" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/twitter%20@Node Eater-0D95E8?style=for-the-badge&logo=twitter&logoColor=white"/></a><br>
 <a href="https://www.facebook.com/ahmadzahirali" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/facebook%20@animenochikara-344E86?style=for-the-badge&logo=facebook&logoColor=white"/></a><br>
 <a href="https://t.me/animenochikara" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/telegram%20@animenochikara-229ED9?style=for-the-badge&logo=telegram&logoColor=white"/></a>
</div><br>

<p align="center">
  <img height="auto" width="auto" src="https://user-images.githubusercontent.com/117473885/204699392-91179431-c1c8-4112-a6f0-53e2863f686f.png">
</p>

## Persyaratan hardware & software


| Erlang Version | Eshell Version | Spesifikasi Hardware | OS | docker version |
|----------------|----------------|----------------------|----|----------------|
| v24.3 | 10.4 |4 core, 4gb ram, 50gb ssd| Ubuntu 20.04 / 22.04|latest (20.10.18 as of September 2022)|

### NOTE : 👉🏻👉🏻👉🏻 KHUSUS YANG SUDAH MENDAPATKAN TOKEN DI BOT YANG DAPAT MENGIKUTI ACARA MINUM TEH 👈🏻👈🏻👈🏻

## 1 . Instal & Update Package

```
sudo apt update
sudo apt upgrade
sudo apt install git
sudo apt install screen
```

## 2 . Open Port

```
ufw allow 22 && ufw allow 1080 && ufw allow 1443 && ufw allow 1800
ufw enable
```

## 3 . Instal Erlang 24.3

#### FOR UBUNTU 22.04

```
apt install cmake clang gcc git curl libssl-dev build-essential automake autoconf libncurses5-dev elixir erlang
```
```
apt -y install erlang-base erlang-public-key erlang-ssl
```

#### FOR UBUNTU 20.04

```
sudo apt install curl wget gnupg apt-transport-https -y
```
```
curl -fsSL https://packages.erlang-solutions.com/ubuntu/erlang_solutions.asc | sudo gpg --dearmor -o /usr/share/keyrings/erlang.gpg
```

```
echo "deb [signed-by=/usr/share/keyrings/erlang.gpg] https://packages.erlang-solutions.com/ubuntu $(lsb_release -cs) contrib" | sudo tee /etc/apt/sources.list.d/erlang.list
```

```
sudo apt update
sudo apt install erlang
```

## 4 . Install Teaclient

```
wget https://tea.thepower.io/teaclient
```

## 5 . Running Teaclient

```
chmod +x teaclient
```
```
./teaclient -n nickname aaaaa.bbbbb
```
<p>
where

 <i><b>teaclient</b></i> — Tea Ceremony client,<br>
<i><b>nickname</b></i> — The name of your node. Maximum 10 characters,<br>
 <i><b>aaaaa.bbbbb</b></i> — Tea Ceremony Token, you've got from the Tea Ceremony bot,<br>
<i><b>-n</b></i> is used with a minus sign, not with a dash.<br>
The token (aaaaa.bbbbb) consists of two parts:<br>

<b>aaaaa</b> — chain token. It is common for all nodes in the chain, and <br>
 <b>bbbbb</b> — personal token. It can't be expired until it is used, but you can use it only once. <br>
If you start the Tea Ceremony with the chain part of the token, you will be able to check the ports availability.

After you have started the client, wait for other participants. Please, DON'T turn off the Tea Ceremony client for 24 hours.
 </p>

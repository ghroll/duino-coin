<!--
*** Official Duino Coin README
*** by revoxhere, 2019-2021
-->

<a href="https://duinocoin.com">
  <img src="https://github.com/revoxhere/duino-coin/blob/master/Resources/duco.png?raw=true" width="215px" align="right" />
</a>

<h1>
  <a href="https://duinocoin.com">
    <img src="https://github.com/revoxhere/duino-coin/blob/master/Resources/ducobanner.png?raw=true" width="430px" />
  </a>
  <br>
  <a href="https://github.com/revoxhere/duino-coin/blob/master/README.md">
    <img src="https://img.shields.io/badge/English-f39c12.svg?style=for-the-badge" /></a>
  <a href="https://github.com/revoxhere/duino-coin/blob/master/Resources/README_TRANSLATIONS/README_es_LATAM.md">
    <img src="https://img.shields.io/badge/-Espa%C3%B1ol-EE5A24?style=for-the-badge" /></a>
  <a href="https://github.com/revoxhere/duino-coin/blob/master/Resources/README_TRANSLATIONS/README_zh_CN.md">
    <img src="https://img.shields.io/badge/简体中文-e74c3c.svg?style=for-the-badge" /></a>
  <a href="https://github.com/revoxhere/duino-coin/blob/master/Resources/README_TRANSLATIONS/README_pl_PL.md">
    <img src="https://img.shields.io/badge/Polski-ED4C67.svg?style=for-the-badge" /></a>
  <a href="https://github.com/revoxhere/duino-coin/blob/master/Resources/README_TRANSLATIONS/README_ru_RU.md">
    <img src="https://img.shields.io/badge/русский-be2edd.svg?style=for-the-badge" /></a>
  <a href="https://github.com/revoxhere/duino-coin/blob/master/Resources/README_TRANSLATIONS/README_tr_TR.md">
    <img src="https://img.shields.io/badge/Türk-5f27cd.svg?style=for-the-badge" /></a>
  <a href="https://github.com/revoxhere/duino-coin/blob/master/Resources/README_TRANSLATIONS/README_th_TH.md">
    <img src="https://img.shields.io/badge/-%E0%B9%84%E0%B8%97%E0%B8%A2-blue.svg?style=for-the-badge" /></a>
  <a href="https://github.com/revoxhere/duino-coin/blob/master/Resources/README_TRANSLATIONS/README_pt_BR.md">
    <img src="https://img.shields.io/badge/-Portugu%C3%AAs-be2edd.svg?style=for-the-badge" /></a>
</h1>
<a href="https://wallet.duinocoin.com">
  <img src="https://img.shields.io/badge/Online Wallet-8e44ad.svg?style=for-the-badge&logo=Web" /></a>
<a href="https://play.google.com/store/apps/details?id=com.pripun.duinocoin">
  <img src="https://img.shields.io/badge/Android App-e84393.svg?style=for-the-badge&logo=Android" /></a>
<a href="https://github.com/revoxhere/duino-coin/blob/gh-pages/assets/whitepaper.pdf">
  <img src="https://img.shields.io/badge/whitepaper-1abc9c.svg?style=for-the-badge&logo=Academia" /></a>
<a href="https://youtu.be/im0Tca7EjrA">
  <img src="https://img.shields.io/badge/Video-Watch-e74c3c.svg?style=for-the-badge&logo=Youtube" /></a>
<a href="https://discord.gg/kvBkccy">
  <img src="https://img.shields.io/discord/677615191793467402.svg?color=5539cc&label=Discord&logo=Discord&style=for-the-badge" /></a>
<a href="https://github.com/revoxhere/duino-coin/releases/latest">
  <img src="https://img.shields.io/badge/release-latest-ff4112.svg?style=for-the-badge" /></a>
<br>

<h3>
  Duino-Coin is a coin that can be mined with Arduinos, ESP8266/32 boards, Raspberry Pis, computers, and many more<br>
  (including Wi-Fi routers, smart TVs, smartphones, smartwatches, SBCs, MCUs or even GPUs)
</h3>


| Key features | Technical specifications | (Some of many) supported boards |
|-|-|-|
| 💻 Supported by a large number of platforms<br>👥 A fast-growing community<br>💱 Easy to use & exchange<br>(on DUCO Exchange, Node-S, JustSwap)<br>🌎 Available everywhere<br>:new: Fully original & open-source project<br>🌳 Beginner & eco-friendly<br>💰 Cost-effective & easy to mine | ⚒️ Algorithms: DUCO-S1, XXHASH,<br>more planned (including PoS)<br>♐ Rewards: supported by "Kolka system"<br>helping to reward miners fairly<br>⚡ Transaction time: Instant<br>🪙 Coin supply: Infinite<br>(before December 2020: 350k coins)<br>(new limits planned for the future)<br>🔤 Ticker: DUCO (ᕲ)<br>🔢 Decimals: up to 20 | ♾️ Arduinos<br>(Uno, Nano, Mega, Due, Pro Mini, etc.)<br>📶 ESP8266s<br>(NodeMCU, Wemos, etc.)<br>📶 ESP32s<br>(ESP-WROOM, ESP32-CAM, etc.)<br>🍓 Raspberry Pis<br>(1, 2, Zero (W/WH), 3, 4, Pico, 400)<br>🍊 Orange Pis<br>(Zero, Zero 2, PC, Plus, etc.)<br>⚡ Teensy 4.1 boards |

## Get started

#### The easiest way to get started with Duino-Coin is to download [the latest release](https://github.com/revoxhere/duino-coin/releases/latest) for your OS.<br>
After downloading the release, unzip it and launch the desired program.<br>
There are no dependencies required.

If you need help, you can take a look at the official getting started guides located <a href="https://duinocoin.com/getting-started">on the official website</a>.<br>
FAQ and troubleshooting help can be found in the [Wikis](https://github.com/revoxhere/duino-coin/wiki).<br>


### Manual installation

#### Linux

```BASH
sudo apt update
sudo apt install python3 python3-pip git python3-pil python3-pil.imagetk -y # Install dependencies
git clone https://github.com/revoxhere/duino-coin # Clone Duino-Coin repository
cd duino-coin
python3 -m pip install -r requirements.txt # Install pip dependencies
````

After doing this, you are good to go with launching the software (e.g. `python3 PC_Miner.py`).


#### Windows

1. Download and install [Python 3](https://www.python.org/downloads/) (make sure you add Python and Pip to your PATH)
2. Download [the Duino-Coin repository](https://github.com/revoxhere/duino-coin/archive/master.zip)
3. Extract the zip archive you've downloaded and open the folder in command prompt
4. In command prompt type `py -m pip install -r requirements.txt` to install required pip dependencies

After doing this, you are good to go with launching the software (just double click on desired `.py` files or type `py PC_Miner.py` in the command prompt).

## Community-made softwares

<details>
  <summary>
    Since that list is getting really long, it's collapsed by default. Click this text to expand it!
  </summary>

  ### Other miners known to work with Duino-Coin:
  *   [Duino-JS](https://github.com/Hoiboy19/Duino-JS) - a JavaScript miner which you can easily implement in your site by Hoiboy19
  *   [Mineuino](https://github.com/VatsaDev/Mineuino) - website monetizer by VatsaDev
  *   [hauchel's duco-related stuff repository](https://github.com/hauchel/duco/) - Collection of various codes for mining DUCO on other microcontrollers
  *   [duino-coin-php-miner](https://github.com/ricardofiorani/duino-coin-php-miner) Dockerized Miner in PHP by ricardofiorani
  *   [duino-coin-kodi](https://github.com/SandUhrGucker/duino-coin-kodi) - Mining addon for Kodi Media Center by SandUhrGucker
  *   [MineCryptoOnWifiRouter](https://github.com/BastelPichi/MineCryptoOnWifiRouter) - Python script to mine Duino-Coin on routers by BastelPichi
  *   [Duino-Coin_Android_Cluster Miner](https://github.com/DoctorEenot/DuinoCoin_android_cluster) - mine with less connections on multiple devices by DoctorEenot
  *   [ESPython DUCO Miner](https://github.com/fabiopolancoe/ESPython-DUCO-Miner) - MicroPython miner for ESP boards by fabiopolancoe
  *   [DUCO Miner for Nintendo 3DS](https://github.com/BunkerInnovations/duco-3ds) - Python miner for Nintendo 3DS by PhereloHD & HGEpro
  *   [Dockerized DUCO Miner](https://github.com/Alicia426/Dockerized_DUCO_Miner_minimal) - Miner in Docker by Alicia426
  *   [nonceMiner](https://github.com/colonelwatch/nonceMiner) - Fastest Duino-Coin miner available by colonelwatch
  *   [NodeJS-DuinoCoin-Miner](https://github.com/DarkThinking/NodeJS-DuinoCoin-Miner/) - simple NodeJS miner by DarkThinking
  *   [d-cpuminer](https://github.com/phantom32-0/d-cpuminer) - pure C miner by phantom32 & revoxhere
  *   [Go Miner](https://github.com/yippiez/go-miner) by yippiez
  *   [ducominer](https://github.com/its5Q/ducominer) by its5Q
  *   [Unofficial miners directory](https://github.com/revoxhere/duino-coin/tree/master/Unofficial%20miners)
      *   [Julia Miner](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Julia_Miner.jl) by revoxhere
      *   [Ruby Miner](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Ruby_Miner.rb) by revoxhere
      *   [Minimal Python Miner (DUCO-S1)](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Minimal_PC_Miner.py) by revoxhere
      *   [Minimal Python Miner (XXHASH)](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Minimal_PC_Miner_XXHASH.py) by revoxhere
      *   [Teensy 4.1 code for Arduino IDE](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Teensy_code/Teensy_code.ino) by joaquinbvw

  ### Other tools:
  *   [DuinoCoin-balance-Home-Assistant](https://github.com/NL647/DuinoCoin-balance-Home-Assistant) - addon for home assistant displaying your balance by NL647
  *   [Duino Coin Status Monitor](https://github.com/TSltd/duino_coin) for 128x64 SSD1306 OLED and ESP8266 by TSltd
  *   [ducopanel](https://github.com/ponsato/ducopanel) - a GUI app for controling your Duino-Coin miners by ponsato
  *   [Duino AVR Monitor](https://www.microsoft.com/store/apps/9NJ7HPFSR9V5) - GUI Windows App for monitoring AVR devices mining DUCO by niknak
  *   [Duino-Coin Arduino library](https://github.com/ricaun/arduino-DuinoCoin) by ricaun
  *   [DuinoCoinI2C](https://github.com/ricaun/DuinoCoinI2C) - Use ESP8266 as a master for Arduinos by ricaun
  *   [Duino-Coin Mining Dashboard](https://lulaschkas.github.io/duco-mining-dashboard/) and troubleshooting helper by Lulaschkas
  *   [duco-miners](https://github.com/dansinclair25/duco-miners) CLI mining dashboard made by dansinclair25
  *   [Duco-Coin Symbol Icon ttf](https://github.com/SandUhrGucker/Duco-Coin-Symbol-Icon-ttf-.h) by SandUhrGucker
  *   [DUCO Browser Extension](https://github.com/LDarki/DucoExtension) for Chrome and derivatives by LDarki
  *   [DUCO Monitor](https://siunus.github.io/duco-monitor/) account statistics website by siunus
  *   [duino-tools](https://github.com/kyngs/duino-tools) written in Java by kyngs
  *   [Duino Stats](https://github.com/Bilaboz/duino-stats) official Discord bot by Bilaboz

  This list will be actively updated. If you want to add software to this list, submit a PR or contact one of the developers.
</details>

## DUCO & wDUCO

Duino-Coin is a hybrid currency, meaning that it can be converted to wDUCO which is DUCO wrapped on the [Tron](https://tron.network) network (as a token). Currently there aren't many uses for it, other than just storing funds in external wallet or exchanging wDUCO to another token on JustSwap. Tutorial on using wDUCO is available in the [wDUCO wiki](https://github.com/revoxhere/duino-coin/wiki/wDUCO-tutorial).

## Development

Contributions are what make the open source community such an amazing place to be learn, inspire, and create.<br>
Any contributions you make to the Duino-Coin project are greatly appreciated.

How to help?

*   Fork the Project
*   Create your feature branch
*   Commit your changes
*   Make sure everything works as intended
*   Open a pull request

Server source code, documentation for API calls and official libraries for developing your own apps for Duino-Coin are available in the [useful tools](https://github.com/revoxhere/duino-coin/tree/useful-tools) branch.

## Benchmarks of officially tested devices and boards

<details>
  <summary>
    Since that table is getting really long, it's collapsed by default. Click this text to expand it!
  </summary>

  | Device/CPU/SBC/MCU/chip                                   | Average hashrate<br>(all threads) | Mining<br>threads | Power<br>usage | Average<br>DUCO/day |
  |-----------------------------------------------------------|-----------------------------------|-------------------|----------------|---------------------|
  | Arduino Pro Mini, Uno, Nano etc.<br>(Atmega 328p/pb/16u2) | 196 H/s                           | 1                 | 0.2 W          | 9-10                |
  | Teensy 4.1 (soft cryptography)                            | 80 kH/s                           | 1                 | 0.5 W          | -                   |
  | NodeMCU, Wemos D1 etc.<br>(ESP8266)                       | 9.3 kH/s (160MHz) 4.6 kH/s (80Mhz)| 1                 | 0.6 W          | 6-7                 |
  | ESP32                                                     | 23 kH/s                           | 2                 | 1 W            | 8-9                 |
  | Raspberry Pi Zero                                         | 17 kH/s                           | 1                 | 1.1 W          | -                   |
  | Raspberry Pi 3                                            | 440 kH/s                          | 4                 | 5.1 W          | -                   |
  | Raspberry Pi 4                                            | 1.3 MH/s                          | 4                 | 6.4 W          | -                   |
  | ODROID XU4                                                | 1.0 MH/s                          | 8                 | 5 W            | 9                   |
  | Atomic Pi                                                 | 690 kH/s                          | 4                 | 6 W            | -                   |
  | Orange Pi Zero 2                                          | 740 kH/s                          | 4                 | 2.55 W         | -                   |
  | Khadas Vim 2 Pro                                          | 1.12 MH/s                         | 8                 | 6.2 W          | -                   |
  | Libre Computers Tritium H5CC                              | 480 kH/s                          | 4                 | 5 W            | -                   |
  | Libre Computers Le Potato                                 | 410 kH/s                          | 4                 | 5 W            | -                   |
  | Pine64 ROCK64                                             | 640 kH/s                          | 4                 | 5 W            | -                   |
  | Intel Celeron G1840                                       | 1.25 MH/s                         | 2                 | -              | 5-6                 |
  | Intel Core i5-2430M                                       | 1.18 MH/s                         | 4                 | -              | 6.5                 |
  | Intel Core i5-3230M                                       | 1.52 MH/s                         | 4                 | -              | 7.2                 |
  | Intel Core i5-5350U                                       | 1.35 MH/s                         | 4                 | -              | 6.0                 |
  | Intel Core i5-7200U                                       | 1.62 MH/s                         | 4                 | -              | 7.5                 |
  | Intel Core i5-8300H                                       | 3.67 MH/s                         | 8                 | -              | 9.1                 |   
  | Intel Core i3-4130                                        | 1.45 MH/s                         | 4                 | -              | -                   |
  | AMD Ryzen 5 2600                                          | 4.9 MH/s                          | 12                | 67 W           | 15.44               |

  All tests were performed using the DUCO-S1 algorithm. This table will be actively updated.
</details>


## License

Duino-Coin is mostly distributed under the MIT License. See `LICENSE` file for more information.
Some third-party included files may have different licenses - please check their `LICENSE` statements (usually at the top of the source code files).

## Terms of service
1. Duino-Coins ("DUCOs") are earned by miners with a process called mining.<br/>
2. Mining is described as using DUCO-S1 (and XXHASH) algorithm (as explained in the <a href="https://github.com/revoxhere/duino-coin/blob/gh-pages/assets/whitepaper.pdf">Duino-Coin Whitepaper</a>), in which finding a correct result to a mathematical problem gives the miner a reward.<br/>
3. Mining can be officially done using CPUs, AVR boards (e.g. Arduino boards), Single-board computers (e.g. Raspberry Pi boards), ESP32/8266 boards with the usage of official miners (other officially allowed miners are described in the upper part of README).<br/>
4. Mining on GPUs, FPGAs and other high-efficiency hardware is allowed, but using only the `EXTREME` mining difficulty.<br/>
5. Any users using miners on difficulty not suited for their hardware (see the <a href="https://github.com/revoxhere/duino-coin/tree/useful-tools#socket-api">difficulty list</a>) will be automatically throttled by being moved to correct difficulty tier.<br/>
6. Any user that keeps trying to use lower difficulty than it's suited for may get temporarily blocked.<br/>
7. Banning involves blocking the user from accessing his coins along with the removal of an account.<br/>
8. Only coins earned legally are eligible for the exchange.<br/>
9. Users spotted using a VPN (or similar) with malicious intents (e.g. bypassing limits) may be banned without prior notice.<br/>
10. Multiple accounts used to bypass limits may be banned without prior notice.<br/>
11. Accounts may be suspended temporarily to investigate ("investigations") ToS violations ("violation" or "abuse").<br/>
12. An exchange request made to the offical DUCO-Exchange ("the offical exchange") may be delayed and/or declined during investigations. <br/>
13. Exchange requests made to the offical exchange may be declined due to ToS violations and/or low funding.<br/>
14. Mining with free cloud hosting services (or free VPS services - e.g. Repl.it, GitHub Actions, etc.) is not allowed.<br />
15. A user's DUCOs may be burnt if a violation can be proven.<br/>
16. These terms of service can change at any time without prior notice.<br/>
17. Every user using Duino-Coin agrees to comply with the above rules.<br/>
## Privacy policy
1. On the master server we only store usernames, hashed passwords (with the help of bcrypt) and e-mails of users as their account data.<br/>
2. E-mails are not publicly available and are only used for contacting user when needed, confirming exchanges on the <a href="https://revoxhere.github.io/duco-exchange/">DUCO-Exchange</a> and receiving an occasional newsletter (planned for the future).<br/>
3. Balances, transactions and mining-related data is publicly available in the public <a href="https://github.com/revoxhere/duino-coin/tree/useful-tools#http-json-api">JSON APIs</a>.<br/>
4. The privacy policy may be changed in the future with a prior notification.

## Active project maintainers

*   [@revoxhere](https://github.com/revoxhere/) - robik123.345@gmail.com (Lead Python dev, project founder)
*   [@Bilaboz](https://github.com/bilaboz/) (Lead NodeJS dev)
*   [@connorhess](https://github.com/connorhess) (Lead Python dev, Node-S owner)
*   [@JoyBed](https://github.com/JoyBed) (Lead AVR dev)
##
*   [@EinWildesPanda](https://github.com/EinWildesPanda) (Dev)
*   [@ygboucherk](https://github.com/ygboucherk) ([wDUCO](https://github.com/ygboucherk/wrapped-duino-coin-v2) dev)
*   [@Tech1k](https://github.com/Tech1k/) - kristian@beyondcoin.io (Webmaster)
*   [@DoctorEenot](https://github.com/DoctorEenot) (Dev)
##
*   [@HGEcode](https://github.com/HGEcode) (Python dev)
*   [@LDarki](https://github.com/LDarki) (Web dev)
*   [@Lulaschkas](https://github.com/Lulaschkas) (Dev)
*   [@Pripun](https://github.com/Pripun) (Mobile apps dev)
*   [@joaquinbvw](https://github.com/joaquinbvw) (AVR dev)

Also big thanks to all [Contributors](https://github.com/revoxhere/duino-coin/graphs/contributors) that helped to develop the Duino-Coin project.

<hr>

Project Link: [https://github.com/revoxhere/duino-coin/](https://github.com/revoxhere/duino-coin/)

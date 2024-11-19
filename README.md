# SEED BOT

## Features  
| Feature                                                   | Supported |
|-----------------------------------------------------------|:---------:|
| Multithreading                                            |     ✅     |
| Proxy binding to session                                  |     ✅     |
| Support for tdata / pyrogram .session |     ✅     |
| Auto-farming                                              |     ✅     |
| Auto-tasks                                                |     ✅     |
| Auto-upgrade                                              |     ✅     |
| Auto-check-in                                             |     ✅     |
| Auto-hunt                                                 |     ✅     |
| Auto-spin                                                 |     ✅     |
| Auto-fusion                                                 |     ✅     |
| Auto-sell worms                                           |     ✅     |


## [Settings](https://github.com/vanhbakaa/Seed-App-Mine-Seed-BOT-Telegram/blob/main/.env-example)

# Use default setting for best performance !
| Settings                |                                 Description                                 |
|-------------------------|:---------------------------------------------------------------------------:|
| **API_ID / API_HASH**   | Platform data from which to run the Telegram session (by default - android) |
| **AUTO_UPGRADE_STORAGE**|                   Auto upgrade storage  (by default - True)                 |
| **AUTO_UPGRADE_MINING** |                  Auto upgrade mining speed (by default - True)              |
| **AUTO_UPGRADE_HOLY**   |                    Auto upgrade holy (by default - True)                    |
| **AUTO_TASK**           |                       Auto tasks (default - True)                           |
| **AUTO_SPIN**     |                    Auto spin (default - True)                         |
| **SPIN_PER_ROUND**     |                    Spin count each round (default - [5, 10])                         |
| **AUTO_FUSION**     |                    Auto fusion eggs if possible (default - True)                         |
| **MAXIMUM_PRICE_TO_FUSION_COMMON**  |                    Max price to fusion common egg (default - 30)                         |
| **MAXIMUM_PRICE_TO_FUSION_UNCOMMON**  |                    Max price to fusion uncommon egg (default - 200)                         |
| **MAXIMUM_PRICE_TO_FUSION_RARE**     |                    Max price to fusion rare egg (default - 800)                         |
| **MAXIMUM_PRICE_TO_FUSION_EPIC**     |                    Max price to fusion epic egg (default - 3000)                         |
| **MAXIMUM_PRICE_TO_FUSION_LEGENDARY**     |                    Max price to fusion legendary egg (default - 20000)                         |
| **AUTO_START_HUNT**     |                    Auto start hunt (default - True)                         |
| **AUTO_SELL_WORMS**     |           Auto sell worms (default - True)                                  |
| **QUANTITY_TO_KEEP**     |    Quantity to keep worms check instruction [here](https://github.com/vanhbakaa/Seed-App-Mine-Seed-BOT-Telegram/blob/main/setting.md)                       |
| **ADVANCED_ANTI_DETECTION**     |   Add more proctection for your account (default: True) |
| **USE_PROXY_FROM_FILE** | Whether to use a proxy from the bot/config/proxies.txt file (True / False)  |

## Quick Start 📚

To fast install libraries and run bot - open run.bat on Windows or run.sh on Linux

## Obtaining API Keys
1. Go to my.telegram.org and log in using your phone number.
2. Select "API development tools" and fill out the form to register a new application.
3. Record the API_ID and API_HASH provided after registering your application in the .env file.


# Installation

```
git clone https://github.com/zyz-airdrops/seed-claimer.git
```
```
cd seed-claimer
```
```
pip install -r requirements.txt
```
```
cp .env-example .env
```
```
nano .env
```
```
python main.py
```

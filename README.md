# Dotcoin Bot

Welcome to the Dotcoin Bot! If you enjoy using this tool, please consider Following to my GitHub and giving this repository a star! :)

## Installation

You can download the repository by cloning it to your system and installing the necessary dependencies:

```bash
git clone https://github.com/rizmyabdulla/dotcoin.git
cd dotcoin
```

1. Download Python (any version).
2. Install the required Python modules: `pip install -r requirements.txt`.
3. Open the Dotcoin Bot on Telegram Web or Telegram Desktop.
4. After opening the bot, access the Developer Tools (F12 or right-click and select "Inspect").
5. In the "Network" tab, look for `get_user_info`.
6. Copy the authorization token (without the "Bearer" prefix).
7. Paste the authorization token into `tokens.txt`.

### Termux Manual Installation

```bash
pkg update && pkg upgrade -y
pkg install python git -y
git clone https://github.com/rizmyabdulla/dotcoin.git
cd dotcoin
pip install -r requirements.txt
nano tokens.txt # Add your accounts token
python main.py
```

## Features  

| Feature                     | Supported |
|-----------------------------|:---------:|
| Multi Account               |    ✅    |
| Auto Gacha (Try your luck)  |    ✅    |
| Auto Complete Tasks         |    ✅    |
| Auto Upgrade Energy         |    ✅    |
| Auto Tap Max Score          |    ✅    |

> **Warning**  
> ⚠️ Using bots is forbidden in all airdrops. I cannot guarantee that you will not be detected as a bot. Use at your own risk. I am not responsible for any consequences of using this software.

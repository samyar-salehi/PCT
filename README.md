# [ProtectionTeam](https://telegram.me/ProtectionTeam)

**An advanced and powerful administration bot based on NEW TG-CLI


* * *

## Commands

| Use help |
|:--------|:------------|
| [#!/]help | just send help in your group and get the commands |

**You can use "#", "!", or "/" to begin all commands

* * *

# Installation

```sh
# Let's install the bot.
cd $HOME
git clone https://github.com/samyar-salehi/PCT.git
cd PCT
chmod +x pct.sh
./pct.sh install
./pct.sh 
# Enter a phone number & confirmation code.
```
### One command
To install everything in one command, use:
```sh
cd $HOME && git clone https://github.com/samyar-salehi/PCT.git && cd PCT && chmod +x pct.sh && ./pct.sh install && ./pct.sh
or 
cd $HOME && git clone https://github.com/samyar-salehi/PCT.git && cd PCT && chmod +x pct.sh && chmod +x auto.sh && ./pct.sh install && ./pct.sh && ./auto.sh
```

* * *

### Sudo

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    104280701,
    0,
    YourID
  }
```
add your ID at line 72 in bot.lua and add your ID at line 2 in tools.lua, Then restart the bot.
    ./auto.sh

# Edit by ssss3456
# [ssss3456](https://telegram.me/ssss3456)



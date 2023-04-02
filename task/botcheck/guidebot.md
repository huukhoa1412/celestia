# Install npm
```
npm install -g npm@8.19.2
mkdir $HOME/cosmos_haqq_bot && cd $HOME/cosmos_haqq_bot
npm install telegraf nodemon axios start --save
```
# Add Telegram bot
- Using [@BotFather](https://t.me/BotFather) to create your BOT, pay attention to HTTP API
- Download the repo, then open `create.js` to add API of your BOT
```
wget -O create.js https://raw.githubusercontent.com/tunguyen9234/celestia/task/botcheck/create.js
```
# Start BOT
```
which screen
#if result return is "/usr/bin/screen" , screen is installed
#if not have screen , run the current command to install
apt install screen
screen -S telebot
```
```
cd $HOME/cosmos_haqq_bot
npm i && npm start
```
# check and use bot , go to t.me/command_celestia_bot
- Start the bot with the command /start , then select the node you want to support
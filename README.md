# GiveawayBot™
[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)

### A Discord Giveaway bot written in Discord.js to create & enjoy Feature rich and Seamless Giveaways within your very own Discord guild!
## Traduit par Pilote Production en français
## Links
- ### This Giveaway Bot Was Created by [ZeroSync](https://youtube.com/c/ZeroSync/)
- [Youtube Channel](https://www.youtube.com/c/ZeroSync)

**Aliter**

### Step 1: Install the Dependencies:
Linux 
```sh
wget https://nodejs.org/dist/v16.18.0/node-v16.18.0-linux-x64.tar.xz
unxz node-v16.18.0-linux-x64.tar.xz
tar xvf node-v16.18.0-linux-x64.tar
mv node-v16.18.0-linux-x64 /usr/local/node

ln /usr/local/node/bin/node /usr/bin
ln /usr/local/node/bin/corepack /usr/bin
ln /usr/local/node/bin/npm /usr/bin

corepack enable
```
Windows 
```sh
# https://nodejs.org/en/blog/release/v16.9.1/ get node.js
npm install 
```

### Step 2: Obtain a Bot Token From [Here](https://discord.com/developers) <br> <br>
### Step 3 : Replace the Token in [config.json](https://github.com/ZeroDiscord/Giveaway/blob/master/config.json) <br>
#### That's all! We Are Done! Now Simply host the Bot!

### Run with node
```sh
node index.js
```
### Run with pm2
```sh
npm install -g pm2@latest
pm2 start --name "Giveaway" index.js --watch
```

# Features
## Featuring | Slash Commands  
### Interactive Giveaway Creation
### Featured ✨ Bonus Entries   
### And Lots More!
- Direct message when the server mentioned for joining is not joined
- Direct message when the server mentioned for joining is joined 
- Direct Message When User Reacts on an ended giveaway
- Direct Message User On Removing Reaction
- Direct Message Winner On Winning

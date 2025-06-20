# guardian-bot

Guardian Bot - The All-in-One Discord Solution✨ 
# Key Features
- Guardian is more than just a moderation bot; it's a complete server management suite built with modern features to keep your community safe, active, and engaged.
- 🛡️ Advanced Moderation: A full suite of moderation tools, including a unique Jail System, logging, timed mutes, warnings, and mass role management.
- 🎟️ Advanced Ticket System: A user-friendly, button-based ticket system for handling member support with ease.
- 🌐 Global Chat: Connect your server with others using Guardian through a configurable, cross-server global chat.
- 🤖 AI Integration: Powered by Google's Gemini, Guardian can answer questions and hold conversations in designated channels.
- 💖 Booster Rewards: A comprehensive system to reward server boosters with custom roles that they can personalize and even share.
- 📅 Daily Content: Keep your server active with automated daily posts, including Quote of the Day, Joke of the Day, and Song of the Day from live APIs.
- 💾 Server Backups: Create and load snapshots of your server's channels and roles, providing peace of mind.
- 🎉 Fun & Utility: A wide range of fun, cute, and utility commands to enhance the user experience.
- 👑 Owner Administration: Secure, owner-only commands for bot administration, including a development mode, status changes, and server management.
- 🚀 Installation & SetupSetting up Guardian is straightforward.
# Follow these steps to get the bot running on your:
```server.PrerequisitesPython 3.8``` or ``newerpip`` for ``package installation1``. Clone the ``RepositoryClone`` this project to your local machine or ``server.git clone <your-repository-url>``
``cd <repository-folder>``
2. Install ``DependenciesInstall`` all the required Python libraries using the ``requirements.txt`` ``file.pip install -r requirements.txt``
*(You will need to create a requirements.txt file containing discord.py, python-dotenv, and aiohttp)3.*
# Configure the ``.env`` File
Create a file named ``.env`` in the root directory of the project. This file will store your secret bot token. Never share this file or your ``token.DISCORD_TOKEN="YOUR_BOT_TOKEN_HERE"``
Replace ``YOUR_BOT_TOKEN_HERE`` with the actual token you get from the Discord Developer Portal.
# 4. Invite the Bot
- Go to the Discord Developer Portal.Navigate to your application, then to OAuth2 > URL Generator. Select the scopes bot and ``applications.commands``. Under "Bot Permissions," select Administrator for the easiest setup. Copy the generated URL and paste it into your browser to invite the bot to your server.
# 5. Run the Bot
- Execute the main file to bring the bot online. ``python main.py``
3 6. Initial Server Setup
- Once the bot is in your server and online, use the following command to configure essential roles and logging. Only the Server Owner can do this. ``/setup log_channel:#your-logs-channel`` ``/setup mod_role:@YourModRole````/setup ticket_support_role:@YourSupportRole`
# 📖 Command Overview
- Guardian uses both slash (/) commands and a prefix (!) for maximum flexibility.
- The help menu is interactive—just type ``/help``!
# Key Command Categories
- Setup (/setup): Configures core bot functions. (Server Owner)
- Moderation (/ban, /kick, /mute, /lock): Tools for managing users and chat. (Moderator Role)
- Jail (/jail, /unjail): Temporarily isolates a user with full role and permission management. (Jail Manager Role)
- Booster Rewards (/boostersetup, /myboosterrole): A complete system for rewarding and managing server boosters with custom roles. (Admin for setup, Boosters for management)
- Daily Content (/setdaily, /toggledaily): Configure automated daily posts from live APIs to keep your community engaged. (Admin)
- Global Chat (/globalchat): Link a channel to a cross-server chat network. (Admin)
- Fun & Cute (/8ball, /hug, /meme): A wide array of commands to entertain your members. (All Users)
- Utility (/userinfo, /serverinfo, /ping): Tools for getting information about users and the server. (All Users)
- AI (/ask, /aisetup): Interact with Google's Gemini AI. (All Users for /ask, Admin for setup)
- Backup (/backup save, /backup load): A powerful, owner-only tool to save and restore a server's entire structure. (Server Owner)
- Owner (/devmode, /shutdown): High-level commands for the bot owner to manage the bot itself. (Bot Owner)🤝
# Contributing
- Contributions are welcome! If you have a suggestion or find a bug, please open an issue to discuss it.

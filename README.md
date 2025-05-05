# TCPASF Discord Bot

<div align="center">
  <img src="https://cdn.discordapp.com/banners/1368957661034577972/a9d313e74c7beef53810a0a2c03da6e7.webp?size=1024" alt="TCPASF Bot Banner" width="600"/>
  
  <p>A powerful, feature-rich Discord bot built with Discord.js v14</p>

  <div>
    <img src="https://img.shields.io/badge/discord.js-v14.14.1-blue.svg" alt="discord.js Version" />
    <img src="https://img.shields.io/badge/node.js-v16.x-green.svg" alt="Node.js Version" />
    <img src="https://img.shields.io/badge/license-MIT-orange.svg" alt="License" />
    <img src="https://img.shields.io/badge/status-active-success.svg" alt="Status" />
  </div>
  
  <div>
    <a href="https://discord.gg/tcpasf">
      <img src="https://img.shields.io/badge/Join-Support%20Server-7289da.svg?style=flat&logo=discord" alt="Support Server" />
    </a>
    <a href="https://tcpasf-dev.thteam.me/">
      <img src="https://img.shields.io/badge/Visit-Website-blue.svg?style=flat&logo=firefox" alt="Website" />
    </a>
  </div>
</div>

## 📋 Table of Contents

- [Features](#-features)
- [Commands](#-commands)
- [Installation](#-installation)
- [Configuration](#-configuration)
- [Usage](#-usage)
- [Contributing](#-contributing)
- [License](#-license)
- [Support](#-support)

## ✨ Features

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
        <br>JavaScript
      </td>
      <td align="center">
        <img width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" />
        <br>Node.js
      </td>
      <td align="center">
        <img width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/discordjs/discordjs-original.svg" />
        <br>Discord.js
      </td>
    </tr>
  </table>
</div>

### Core Features

- **🎫 Advanced Ticket System**
  - Create, manage, and close support tickets
  - Ticket transcripts and logging
  - Customizable ticket categories
  - Staff management for tickets

- **🎉 Giveaway System**
  - Create and manage giveaways
  - Multiple winners support
  - Reroll functionality
  - Giveaway requirements and bonus entries

- **👋 Welcome System**
  - Customizable welcome messages
  - Beautiful welcome cards with Canvas
  - Server information for new members
  - Invite tracking

- **🎮 Interactive Games**
  - TicTacToe, Connect4, Hangman
  - Word Search, Math Quiz, Trivia
  - Memory Game, Rock Paper Scissors
  - Slot Machine, Coin Flip, Dice Roll

- **🛡️ Moderation Tools**
  - Ban, kick, mute, timeout
  - Message purging
  - Channel management (lock/unlock)
  - Warning system

- **📊 Logging System**
  - Message logging
  - Member join/leave logging
  - Voice channel activity
  - Server changes

- **🔗 Invite Tracking**
  - Track who invited whom
  - Invite leaderboard
  - Fake account detection

- **🤖 Utility Commands**
  - User info, server info
  - Avatar and banner viewing
  - Role information
  - Statistics and ping

## 🤖 Commands

The bot features a wide range of commands organized into categories:

### 📚 Public Commands
- `/help` - Shows all available commands
- `/ping` - Check the bot's latency
- `/user` - View user information
- `/server` - View server information
- `/avatar` - View a user's avatar
- `/banner` - View a user's banner
- `/invite` - Get the bot's invite link
- `/stats` - View bot statistics

### 🎮 Game Commands
- `/tictactoe` - Play Tic Tac Toe
- `/connect4` - Play Connect 4
- `/hangman` - Play Hangman
- `/wordsearch` - Play Word Search
- `/mathquiz` - Play Math Quiz
- `/trivia` - Play Trivia
- `/memorygame` - Play Memory Game
- `/rps` - Play Rock Paper Scissors
- `/slotmachine` - Play Slot Machine
- `/coinflip` - Flip a coin
- `/roll` - Roll a dice

### 🎉 Giveaway Commands
- `/giveaway start` - Start a new giveaway
- `/giveaway end` - End a giveaway early
- `/giveaway reroll` - Reroll a giveaway winner
- `/giveaway list` - List all active giveaways
- `/giveaway info` - Get information about a giveaway
- `/giveaway pause` - Pause a giveaway
- `/giveaway resume` - Resume a paused giveaway

### 🎫 Ticket Commands
- `/ticket setup` - Set up the ticket system
- `/ticket close` - Close a ticket
- `/ticket add` - Add a user to a ticket
- `/ticket remove` - Remove a user from a ticket
- `/ticket transcript` - Generate a transcript of a ticket
- `/ticket config` - View the ticket system configuration
- `/ticket panel` - Resend the ticket panel

### 🛡️ Moderation Commands
- `/ban` - Ban a user
- `/kick` - Kick a user
- `/mute` - Mute a user
- `/timeout` - Timeout a user
- `/clear` - Clear messages
- `/lock` - Lock a channel
- `/unlock` - Unlock a channel
- `/warn` - Warn a user
- `/warnings` - View a user's warnings

### 👑 Admin Commands
- `/setup-logs` - Set up the logging system
- `/setup-modlogs` - Set up the moderation logs
- `/unbanall` - Unban all users
- `/come` - Make the bot join your voice channel

### 🔧 Other Commands
- `/autoReply` - Set up auto-replies
- `/boost` - Configure boost messages
- `/botvoice` - Configure bot voice settings
- `/feedback` - Set up feedback system
- `/totalrate` - View server ratings
- `/welcome` - Configure welcome messages

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/tcpasf-bot.git
   cd tcpasf-bot
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure the bot**
   - Rename `config.example.json` to `config.json`
   - Fill in your bot token and other required information

4. **Start the bot**
   ```bash
   npm start
   ```

## ⚙️ Configuration

The bot uses a configuration system stored in JSON files:

### Main Configuration (`config.json`)
```json
{
  "token": "YOUR_BOT_TOKEN",
  "clientId": "YOUR_CLIENT_ID",
  "ownerid": "YOUR_DISCORD_ID"
}
```

### Guild Configuration (`data/config.json`)
This file stores server-specific settings like welcome messages, ticket system, and more.

## 🔍 Usage

1. **Invite the bot to your server** using the link provided by the `/invite` command
2. **Set up the bot** using the configuration commands
3. **Use the `/help` command** to see all available commands

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🆘 Support

If you need help with the bot, join our [support server](https://discord.gg/tcpasf) or visit our [website](https://tcpasf-dev.thteam.me/).

---

<div align="center">
  <p>Made with ❤️ by TCPASF Development Team</p>
  
  <a href="https://discord.gg/tcpasf">
    <img src="https://img.shields.io/discord/1368933359849439254?color=5865F2&logo=discord&logoColor=white" alt="Discord server" />
  </a>
</div>

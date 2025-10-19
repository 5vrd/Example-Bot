# Modular Discord Bot Template

A fully modular Discord bot template written in JavaScript using Discord.js v14.  
This bot template is designed to be **scalable, maintainable, and easy to customize**.  
It includes a clear folder structure, separate command and event handlers, utility functions, and logging features.  
Perfect for beginners and advanced developers who want a solid starting point for any Discord bot project.

---

## Features

- **Modular commands system**: Easily add, remove, or modify commands.
- **Event handling system**: Handles events like `ready`, `messageCreate`, and custom events.
- **Logger utility**: Simple logging for development and debugging.
- **Scalable structure**: Organized folders for commands, events, handlers, utilities, and configuration.
- **Ready for GitHub deployment**: Everything structured to push and share on GitHub.
- **Example commands included**: `ping` command as a starter.
- **Modern Discord.js v14 support**: Uses the latest Discord.js features and intents.
- **Flexible prefix system**: Change the prefix easily in the configuration file.
- **Error handling included**: Catches errors in commands and logs them.

---

## Folder Structure
src
├── commands/ # All bot commands
│ └── ping.js
├── events/ # Bot event handlers
│ ├── ready.js
│ └── message.js
├── handlers/ # Load commands and events dynamically
│ ├── commandHandler.js
│ └── eventHandler.js
├── utils/ # Utility functions (e.g., logger)
│ └── logger.js
├── config/ # Configuration files
│ └── config.json
├── index.js # Main bot file
├── package.json # Node.js dependencies
└── .gitignore # Files and folders to ignore in Git


This folder structure allows you to **easily scale your bot** by adding more commands, events, or utilities without cluttering the main file.

---

## Installation

1. **Clone this repository:**

```bash
git clone https://github.com/your-username/my-bot.git
cd src


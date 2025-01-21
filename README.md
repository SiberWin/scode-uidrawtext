<div align="center">
  
# SCODE UI Draw Text System
### Modern and Elegant Notification System for FiveM

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Discord](https://img.shields.io/discord/YOUR_DISCORD_ID?color=7289da&label=Discord&logo=discord&logoColor=ffffff)](https://discord.gg/DqnAqdR22d)
[![Tebex](https://img.shields.io/badge/Tebex-Store-brightgreen)](https://scode.tebex.io)


</div>

## 🌟 Features

- 🎨 Modern and Clean UI Design
- 🎵 Sound Effects for Different Notification Types
- 🌈 Multiple Notification Styles (Default, Success, Warning, Error)
- ⚡ Optimized Performance (0.00ms when idle)
- 🔄 Automatic Version Checker
- 📱 Fully Responsive Design
- 🎮 Easy to Integrate with any Framework

## 📥 Installation

1. Download the latest version from [Tebex Store](https://scode.tebex.io)
2. Extract `scode-uidrawtext` to your resources folder
3. Add `ensure scode-uidrawtext` to your server.cfg

## 💻 Usage Examples

### Basic Notification
```lua
exports["scode-uidrawtext"]:SendUI("TITLE", "Your message here")
```

### Success Notification
```lua
exports["scode-uidrawtext"]:SendSuccessUI("SUCCESS", "Operation completed successfully!")
```

### Warning Notification
```lua
exports["scode-uidrawtext"]:SendWarningUI("WARNING", "Please be careful!")
```

### Error Notification
```lua
exports["scode-uidrawtext"]:SendErrorUI("ERROR", "Something went wrong!")
```

### Close Notification
```lua
exports["scode-uidrawtext"]:CloseUI()
```

## 🎮 Practical Examples

```lua
-- Door interaction example
exports["scode-uidrawtext"]:SendUI("DOOR", "[E] Press to open")

-- Shop notification
exports["scode-uidrawtext"]:SendUI("SHOP", "[E] Open shop menu")

-- Vehicle interaction
exports["scode-uidrawtext"]:SendUI("VEHICLE", "[G] Open trunk")
```

## ⚙️ Configuration
No configuration needed! The script works out of the box with optimal settings.

## 🔧 Support
- For support, join our [Discord Server](https://discord.gg/DqnAqdR22d)
- Check our [Tebex Store](https://scode.tebex.io) for updates
- Visit [our website](https://siberwin.com) for more scripts

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Credits
Created with ❤️ by SCODE SiberWin  Studios

<div align="center">
  <img src="logo.png" alt="SCODE Logo" width="200"/>
  
  **[Discord](https://discord.gg/DqnAqdR22d)** | **[Tebex](https://scode.tebex.io)** | **[Website](https://siberwin.com)**
</div>







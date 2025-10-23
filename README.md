# Riot Account Manager

A lightweight account manager for Riot Client with auto-login functionality. Designed for players managing multiple League of Legends accounts.

## Features

- **Encrypted Account Storage** - All passwords are securely encrypted and saved locally
- **Auto-Login** - Instantly fill credentials and login to Riot Client with one click
- **Account Management** - Add, edit, or delete accounts easily
- **Persistent Storage** - Accounts are saved in JSON format
- **Modern UI** - Dark theme with minimalist and intuitive design
- **Stay Signed In Support** - Optional "Remember Me" checkbox per account

## System Requirements

- Windows 7 or later
- .NET Framework 4.7.2+
- Visual Studio 2019+ (for building from source)

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/LEATERNx/RiotLogin.git
cd RiotLogin
```

### 2. Build
- Open Visual Studio
- Build → Build Solution (Ctrl+Shift+B)
- Find the .exe in `bin/Release/` folder

## Usage

1. **Run the Application** - Launch RiotAccountManager.exe
2. **Add Account** - Click ➕ Add button
3. **Enter Credentials** - Fill in Account Name, Username, and Password
4. **Open Riot Client** - Make sure Riot Client is running
5. **Login** - Select an account and click 🚀 Login

## Disclaimer

By using this tool, you acknowledge and accept all risks associated with its use. 
Any consequences, account bans, or issues that arise from using Riot Account Manager 
are solely your responsibility. The creator assumes no liability for any damages or 
losses incurred. Use at your own risk.

### Options
- **Auto Login** - Automatically submit credentials when enabled
- **Stay Signed In** - Check the "Remember Me" option

## Security Warning

- Passwords are encrypted with basic XOR encryption (not production-grade)
- Keep `accounts.json` file secure and private
- **Terms of Service**: Check Riot Games ToS before using. Use at your own risk.
- Do not share this tool or run it on others' computers

## Project Structure

```
RiotLogin/
├── MainForm.cs         # Main application + all classes
├── accounts.json       # Saved accounts (.gitignore)
├── riot.ico           # Application icon (optional)
└── README.md
```

## Class Overview

| Class | Purpose |
|-------|---------|
| `Account` | Data model for account information |
| `AccountManager` | Handle loading, saving, encryption/decryption |
| `RiotAutoFill` | Automate Riot Client form filling |
| `MainForm` | Main UI window |
| `AddAccountForm` | Account creation/editing dialog |

## Contributing

Found a bug or have an idea? Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## License

MIT License - See `LICENSE` file for details

## Support

If you encounter issues or have suggestions, feel free to open an Issue on GitHub!

---

**Author:** LEATERNx  
**Last Updated:** October 2025  
**Repository:** https://github.com/LEATERNx/RiotLogin
Thanks @lithellx for the inspiration!


![Downloads](https://img.shields.io/github/DOWNLOADS/LEATERNx/RiotLogin/total)


[![Riot Account Manager](https://img.youtube.com/vi/24KIKuA-GGE/hqdefault.jpg)](https://www.youtube.com/watch?v=24KIKuA-GGE)

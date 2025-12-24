# Garena Free Fire Guest Account Generator 🌸

![Free Fire](https://img.shields.io/badge/Free%20Fire-Guest%20Account%20Generator-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.7%2B-green?style=for-the-badge&logo=python)
![Multi-Threaded](https://img.shields.io/badge/Multi--Threaded-Yes-success?style=for-the-badge)
![License](https://img.shields.io/badge/Educational%20Use-Only-red?style=for-the-badge)

## 📖 Description

A sophisticated Python-based tool for generating guest accounts for Garena Free Fire across multiple regions. This tool features multi-threaded generation, automatic account classification, and secure storage with JSON formatting.

## ✨ Features

- **🌍 Multi-Region Support**: Generate accounts for 11+ regions (IND, ID, BR, ME, VN, TH, CIS, BD, PK, SG, SAC, TW)
- **👻 Ghost Mode**: Special mode for unique account generation
- **💎 Rarity Detection**: Automatic detection of rare account patterns (sequential numbers, palindromes, special combinations)
- **💑 Couples Accounts**: Intelligent pairing of complementary account IDs
- **🧵 Multi-Threading**: Parallel account generation for increased speed
- **🔐 JWT Token Generation**: Automatic JWT token acquisition and storage
- **📁 Organized Storage**: Accounts sorted by region and type with thread-safe file operations
- **🎨 Colorful Interface**: Color-coded console output for better visibility
- **⚡ Performance Metrics**: Real-time progress tracking and speed statistics

## 📦 Installation

### Prerequisites
- Python 3.7 or higher
- pip package manager

### Step-by-Step Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/Garena-FreeFire-Guest-Account-Generator.git
cd Garena-FreeFire-Guest-Account-Generator
```

2. **Install required packages**
The script will automatically check and install required dependencies:
- `requests`
- `pycryptodome`
- `colorama`
- `urllib3`
- `psutil`

3. **Run the script**
```bash
python Garena-Free-Fire-Guest-Account-Generator.py
```

## 🚀 Usage

### Main Menu Options

1. **Generate Accounts** - Start account generation
   - Select region or Ghost Mode
   - Specify number of accounts
   - Set account name prefix
   - Configure password prefix
   - Adjust rarity threshold
   - Set thread count

2. **View Saved Accounts** - Browse generated accounts
   - View account counts by region
   - Check total saved accounts

3. **About** - Project information and features
   - Features list
   - Storage locations
   - Disclaimer

### Account Generation Flow

```
Region Selection → Configuration → Multi-threaded Generation → Storage
```

### Storage Structure
```
Garena Free Fire Guest Account 🌸/
├── JWT Token 🔑/
├── Guest Accounts 🌸/
├── Rare Guest Accounts ❤/
├── Couples Account 💝/
└── 𝐆𝐇𝐎𝐒𝐓/
    ├── Guest Accounts 🌸/
    ├── Rare Guest Accounts ❤/
    └── Couples Account 💝/
```

## ⚙️ Configuration

### Region Codes
| Code | Language | Server |
|------|----------|--------|
| IND  | Hindi    | India |
| ID   | Indonesian | Indonesia |
| BR   | Portuguese | Brazil |
| ME   | Arabic   | Middle East |
| VN   | Vietnamese | Vietnam |
| TH   | Thai     | Thailand |
| CIS  | Russian  | CIS |
| BD   | Bengali  | Bangladesh |
| PK   | Urdu     | Pakistan |
| SG   | English  | Singapore |
| SAC  | Spanish  | South America |
| TW   | Chinese  | Taiwan |

### Rarity Patterns Detected
- **Repeated Digits**: 1111, 2222, etc.
- **Sequential Numbers**: 12345, 23456, etc.
- **Palindromes**: 123321, 1221, etc.
- **Special Combinations**: 69, 420, 1337, 007
- **Mirror Patterns**: 12021, 123321
- **Love Numbers**: 520, 521, 1314

## ⚠️ Disclaimer

**IMPORTANT**: This tool is for **educational and research purposes only**. 

- The use of this software may violate Garena Free Fire's Terms of Service
- Automated account generation is against most game policies
- Use at your own risk
- Not intended for commercial use
- The developer is not responsible for any consequences resulting from the use of this tool

## 🔧 Technical Details

### Key Components
1. **Account Generation**: Uses Garena's guest registration API
2. **Encryption**: AES encryption for secure communication
3. **Multi-threading**: Thread-safe operations with locking mechanisms
4. **Pattern Detection**: Regex-based pattern matching for account classification
5. **File Management**: Atomic file operations to prevent corruption

### Safety Features
- Thread-safe file writing
- Atomic file operations with temporary files
- Graceful exit handling (Ctrl+C support)
- Error recovery mechanisms

## 📊 Performance

- **Speed**: Up to 2-3 accounts/second (depends on thread count)
- **Storage**: JSON format with UTF-8 encoding
- **Memory**: Efficient memory usage with streaming JSON writing

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is for educational purposes only. All rights belong to their respective owners.

## 👤 Author

**SPIDEERIO GAMING**
- Discord: https://discord.gg/f2Xrk6aH8N
- Project maintained for educational purposes

## 🙏 Acknowledgments

- Thanks to the Python community for excellent libraries
- Educational purpose only - no affiliation with Garena or Free Fire

---

**Note**: This tool is meant for learning about API interactions, multi-threading, and pattern recognition. Always respect game developers' terms of service and community guidelines.

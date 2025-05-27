# 🔐 Caesar Cipher

> A simple and interactive Python implementation of the classic Caesar cipher encryption technique.

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![100 Days of Code](https://img.shields.io/badge/100%20Days%20of%20Code-Day%208-orange?style=flat-square)

## 📖 About

This project is part of **Angela Yu's 100 Days of Code: The Complete Python Pro Bootcamp** (Day 8). The Caesar cipher is one of the simplest and most widely known encryption techniques, where each letter in the plaintext is shifted a certain number of places down or up the alphabet.

## ✨ Features

- 🔒 **Encode** messages with custom shift values
- 🔓 **Decode** encrypted messages back to original text
- 🎨 **ASCII Art Logo** for a beautiful command-line interface
- 🔤 **Preserves Non-Alphabetic Characters** (spaces, punctuation, numbers)
- 🔄 **Interactive Loop** - perform multiple operations without restarting
- 📝 **Case Insensitive** - handles both uppercase and lowercase input

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- `art` module for ASCII logo display

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/qusai-Kagalwala/caesar-cipher.git
   cd caesar-cipher
   ```

2. **Install required dependencies**
   ```bash
   pip install art
   ```

3. **Run the program**
   ```bash
   python main.py
   ```

## 🎮 How to Use

1. **Start the program** - You'll see the ASCII art logo
2. **Choose operation** - Type `encode` to encrypt or `decode` to decrypt
3. **Enter your message** - Type the text you want to process
4. **Set shift amount** - Enter a number for how many positions to shift
5. **View results** - See your encoded/decoded message
6. **Continue or exit** - Choose to perform another operation or quit

### Example Usage

```
Type 'encode' to encrypt, type 'decode' to decrypt:
encode

Type your message:
hello world

Type the shift number:
5

Here is the encoded result: mjqqt btwqi

Type 'yes' if you want to go again. Otherwise, type 'no'.
yes

Type 'encode' to encrypt, type 'decode' to decrypt:
decode

Type your message:
mjqqt btwqi

Type the shift number:
5

Here is the decoded result: hello world
```

## 🔧 How It Works

The Caesar cipher uses a simple substitution method:

1. **Encoding**: Each letter is shifted forward in the alphabet by the specified amount
2. **Decoding**: Each letter is shifted backward in the alphabet by the specified amount
3. **Wrap-around**: When reaching the end of the alphabet, it wraps to the beginning (z + 1 = a)
4. **Non-alphabetic preservation**: Spaces, numbers, and punctuation remain unchanged

### Algorithm Visualization

```
Original:  A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
Shift +3:  D E F G H I J K L M N O P Q R S T U V W X Y Z A B C
```

## 📁 Project Structure

```
caesar-cipher/
├── main.py          # Main program file
├── art.py           # ASCII art logo (if separate file)
└── README.md        # Project documentation
```

## 🎓 Learning Objectives

This project demonstrates:
- ✅ **Functions and Parameters** - Creating reusable code blocks
- ✅ **String Manipulation** - Processing text character by character
- ✅ **List Operations** - Using alphabet list for character mapping
- ✅ **Conditional Logic** - Handling encode vs decode operations
- ✅ **Loops and Flow Control** - Interactive program flow
- ✅ **Modulo Operations** - Wrapping around the alphabet
- ✅ **User Input Handling** - Interactive command-line interface

## 🤝 Contributing

Contributions are welcome! Feel free to:
- 🐛 Report bugs
- 💡 Suggest new features
- 🔧 Submit pull requests
- 📚 Improve documentation

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Angela Yu** - For the amazing 100 Days of Code Python Bootcamp
- **Historical Caesar** - For the original cipher technique
- **Python Community** - For the excellent documentation and resources

## 📞 Connect

- GitHub: [@qusai-Kagalwala](https://github.com/qusai-Kagalwala)

---

⭐ **Star this repository if you found it helpful!** ⭐

*Made with ❤️ as part of the 100 Days of Code challenge*

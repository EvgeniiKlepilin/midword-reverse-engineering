# midword-reverse-engineering

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)
![Prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)
![Reverse Engineering](https://img.shields.io/badge/type-reverse%20engineering-red.svg)

Reverse engineering analysis of [Midword.com](https://midword.com) online word game to understand its client-side mechanics and reveal the secret word functionality. The article going into the details about this project can be found on my blog: [Reverse Engineering MidWord.com](https://evgeniipendragon.com/posts/reverse-engineering-midword-com/)

## 📋 Overview

This project contains a reverse-engineered analysis of the Midword.com word guessing game. Through client-side code analysis, I've identified and extracted the core game functionality that allows discovering the secret word without actually playing through the game normally.

## 🔍 What's Inside

- **`midword.js`** - The original client-side JavaScript code from Midword.com, prettified and analyzed
- **Key findings** - Game logic vulnerabilities that expose the secret word mechanism
- **Code analysis** - Documented methods for extracting game solutions

## 🎯 Key Discoveries

Through reverse engineering the client-side code, this project reveals:

- How the secret word is stored and accessed in the browser
- Game logic flaws that allow bypassing normal gameplay
- Client-side vulnerabilities in the word validation system
- Methods to programmatically extract the secret word solution

## 🛠️ Technical Details

### Code Formatting
The original minified JavaScript has been processed using Prettier for better readability and analysis:

```bash
npm install
npx prettier --write midword.js
```

### Analysis Approach
1. **Code Beautification** - Used Prettier to format the minified source
2. **Function Identification** - Located key game logic functions
3. **Variable Tracking** - Traced secret word storage and retrieval
4. **Vulnerability Assessment** - Identified client-side security gaps

## 📁 Project Structure

```
midword-reverse-engineering/
├── .gitignore              # Node modules exclusion
├── .prettierrc            # Prettier configuration
├── .prettierignore        # Prettier ignore rules
├── LICENSE                # MIT License
├── README.md              # This file
├── package.json           # Project configuration
└── midword.js             # Analyzed game code
```

## ⚠️ Educational Purpose

This project is intended for:
- **Educational analysis** of client-side game security
- **Understanding** common web game vulnerabilities  
- **Research purposes** in reverse engineering techniques
- **Security awareness** for game developers

## 🚀 Usage

1. Clone the repository:
```bash
git clone https://github.com/EvgeniiKlepilin/midword-reverse-engineering.git
cd midword-reverse-engineering
```

2. Install dependencies:
```bash
npm install
```

3. Analyze the code:
- Examine `midword.js` for game logic
- Look for secret word extraction methods
- Study client-side validation bypasses

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚖️ Disclaimer

This project is for educational and research purposes only. The analysis is performed on publicly accessible client-side code.

---

*Happy reverse engineering! 🔍*

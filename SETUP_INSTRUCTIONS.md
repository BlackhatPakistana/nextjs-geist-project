# BIN Generator - Cyberpunk Educational Tool

## 🎯 Project Overview
This is an educational BIN (Bank Identification Number) generator with a cyberpunk hacker theme. It demonstrates credit card validation algorithms and BIN systems for learning purposes only.

## ⚠️ IMPORTANT DISCLAIMER
**FOR EDUCATIONAL PURPOSES ONLY** - This tool is designed exclusively for learning about credit card validation algorithms. DO NOT use for fraudulent activities.

## 🚀 Quick Setup

### Prerequisites
- Node.js 18+ installed on your system
- npm or yarn package manager

### Installation Steps

1. **Extract the zip file** to your desired location

2. **Navigate to the project directory**
   ```bash
   cd bin-generator-cyberpunk
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser** and visit:
   ```
   http://localhost:3000
   ```

## 🎨 Features

### Core Functionality
- ✅ **BIN Generation**: Generate valid BINs for 10 countries
- ✅ **Country Filter**: USA, UK, Canada, Germany, France, Italy, Spain, Netherlands, Australia, Japan
- ✅ **VBV/Non-VBV Options**: Toggle between verification modes
- ✅ **Download as TXT**: Export generated BINs to text file
- ✅ **Luhn Validation**: All numbers pass credit card validation algorithms

### Cyberpunk Design
- 🎯 **Dark Theme**: Black/gray backgrounds with neon accents
- 🎯 **Neon Colors**: Green and cyan glowing effects
- 🎯 **Hacker Fonts**: Orbitron and Fira Code monospace fonts
- 🎯 **Interactive Elements**: Glowing borders and hover animations
- 🎯 **Professional Layout**: Clean, modern interface

## 📁 Project Structure

```
bin-generator-cyberpunk/
├── src/
│   ├── app/
│   │   ├── layout.tsx          # Main layout with fonts
│   │   ├── page.tsx            # Main BIN generator page
│   │   └── globals.css         # Global styles
│   ├── components/
│   │   ├── Disclaimer.tsx      # Educational disclaimer
│   │   ├── BinFilter.tsx       # Country/VBV selection
│   │   ├── BinDisplay.tsx      # Generated BINs display
│   │   ├── DownloadButton.tsx  # TXT export functionality
│   │   └── ui/                 # Shadcn UI components
│   ├── lib/
│   │   ├── binGenerator.ts     # Core BIN generation logic
│   │   └── utils.ts            # Utility functions
│   └── styles/
│       └── cyberpunk.css       # Custom cyberpunk styling
├── public/                     # Static assets
├── package.json               # Dependencies and scripts
└── README.md                  # This file
```

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 🛠️ Technology Stack

- **Framework**: Next.js 15 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS + Custom Cyberpunk Theme
- **UI Components**: Shadcn/ui
- **Fonts**: Google Fonts (Orbitron, Fira Code)

## 🎓 Educational Information

### What is a BIN?
- BIN = Bank Identification Number
- First 6 digits of a credit card number
- Identifies the issuing bank and card type

### Luhn Algorithm
- Mathematical formula for validating credit card numbers
- Also known as "modulus 10" algorithm
- Detects simple errors in credit card numbers

### VBV vs Non-VBV
- VBV = Verified by Visa
- Additional security layer for online transactions
- Non-VBV cards don't require additional verification

## ⚖️ Legal Notice

This tool is created for educational purposes only. Users are responsible for complying with all applicable laws. Misuse for fraudulent purposes is illegal and strictly prohibited.

## 🐛 Troubleshooting

### Port Already in Use
If you get a port error, try:
```bash
# Kill process on port 3000
npx kill-port 3000
# Or use a different port
npm run dev -- -p 3001
```

### Dependencies Issues
```bash
# Clear npm cache
npm cache clean --force
# Delete node_modules and reinstall
rm -rf node_modules package-lock.json
npm install
```

## 📞 Support

This is an educational project. For learning purposes, you can:
1. Study the code structure
2. Modify the cyberpunk styling
3. Add new countries or BIN prefixes
4. Enhance the UI/UX

---

**Remember**: This tool is for educational purposes only. Always use technology responsibly and ethically.

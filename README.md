# 🔐 Encryption Toolkit

A modern, full-featured, and responsive encryption tool built using HTML, CSS, and JavaScript — all wrapped in a beautiful dark theme. This web-based toolkit allows you to encode and decode text using a wide variety of encryption algorithms, including both classic and modern techniques. It supports saving, file input, audio playback for Morse code, and universal decryption.

---

## 🚀 Features

### ✅ Core Encryption & Decryption Methods
- **Caesar Cipher** (with adjustable shift value, lowercase + uppercase support)
- **Vigenère Cipher**
- **Base64 Encoding / Decoding**
- **URL-safe Base64 Encoding / Decoding**
- **Morse Code Encoding / Decoding**
  - 🔊 **Audio playback with adjustable speed and pitch**
  - 💡 **Visual blinking indicator (optional)**
- **Reverse Text**
- **ROT13 Cipher**
- **Universal Decryption** (attempts to automatically detect and decrypt encoded content)

---

### 🧰 Toolkit Utilities
- 🔁 Encode & Decode in real time
- 💾 Save output to `.txt` file
- 📂 Load input from text files
- 📋 Copy result to clipboard
- 🎛️ Intuitive UI with:
  - Dropdown for method selection
  - Checkbox for decryption toggle
  - Dynamic interface (buttons appear only when needed)
- 🔊 Morse sound button appears only in encoding mode
- 🎨 **Dark theme only** for distraction-free experience

---

## 📸 Screenshots

> _(You can add screenshots here)_

- Interface preview
- Caesar Cipher example
- Morse Code with audio and blinking
- File upload & save usage

---

## 🧠 How It Works

The UI is powered by vanilla JavaScript and allows you to select encryption types dynamically. Each method is implemented with its own encoding/decoding logic.

### Example Flow:
1. Enter text in the input box.
2. Choose an encryption method from the dropdown.
3. (Optional) Enable decryption mode.
4. Click **Process** to view results.
5. Use **Copy**, **Save**, or **Play Morse** (if enabled).

---

## 🛠️ Installation & Usage

### Local HTML File
1. Download the `encryption_toolkit.zip` from the [Releases](#).
2. Extract the folder.
3. Open `index.html` in any modern browser (Chrome, Firefox, Edge, etc).
4. No internet required — fully offline.

### Optional (GitHub Pages Hosting)
To host online:
- Fork this repo
- Push the code to the `main` branch
- Enable GitHub Pages in repo settings
- Done!

---

## 🌐 Encryption Methods Included

| Method        | Encrypt | Decrypt | Description |
|---------------|---------|---------|-------------|
| Caesar Cipher | ✅      | ✅      | Rotational cipher with a fixed shift |
| Vigenère      | ✅      | ✅      | Polyalphabetic cipher using key |
| Base64        | ✅      | ✅      | Encodes binary into text-safe string |
| URL Base64    | ✅      | ✅      | Base64 variant safe for URLs |
| Morse Code    | ✅      | ✅      | Dots and dashes (audio + text) |
| Reverse       | ✅      | ✅      | Simply reverses string |
| ROT13         | ✅      | ✅      | 13-shift Caesar (same for enc/dec) |
| Universal Decrypt | ❌ | ✅ | Attempts to guess and decrypt format |

---

## 👨‍💻 Contribution

Contributions are welcome! Here's how:
1. Fork the repository
2. Create a new branch: `feature/your-feature-name`
3. Commit your changes
4. Push to the branch and open a pull request

Ideas for improvement:
- Add more ciphers (Playfair, XOR, Affine, etc.)
- Make mobile UI even more compact
- Add animation on encode/decode
- Export encrypted data as QR Code

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, modify, and distribute with attribution.

---

## 🤝 Support & Acknowledgments

If you like this project, leave a ⭐️ star on GitHub.  
Built with ❤️ using HTML, CSS, and JavaScript.

---

## 🔗 Links

- [Live Demo (if hosted)](#)
- [Download Latest Version](#)
- [Report Bug / Suggest Feature](https://github.com/AmitzGaming/Encryption_Toolkit/issues)



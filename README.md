# Text Encoder–Decoder Tool (Python)

A Python-based text encoder–decoder that applies custom string manipulation
and reversible encoding logic. The program encodes user input using defined
rules and decodes it back to its original form.

---

## 📌 Overview

This project implements a rule-based text encoding and decoding system.
The encoding process rearranges characters in the input string and adds
randomized padding, while the decoding process accurately reverses the
transformation to recover the original text.

The project focuses on strengthening understanding of string immutability,
slicing, control flow, and logical reversibility in Python.

---

## ✨ Features

- Encode text using custom transformation rules
- Decode encoded text back to the original string
- Handles edge cases for short strings
- Menu-driven command-line interface
- Reversible and deterministic logic

---

## 🛠️ Technologies Used

- Python
- String manipulation
- Randomization (`random` module)

---

## ⚙️ Encoding Rules

- If the string length is **less than 3**:
  - The string is reversed
- If the string length is **greater than 3**:
  - The first character is removed and appended to the end
  - Three random lowercase letters are added to the front
  - Three different random lowercase letters are added to the back

---

## 🔄 Decoding Rules

- If the string length is **less than 3**:
  - The string is reversed
- Otherwise:
  - The first and last three random characters are removed
  - The last character is moved back to the front to reconstruct the original string

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   https://github.com/Arpitawork24/Text-Encoder-Decoder.git
2. Navigate to the project directory:
  cd Text-Encoder-Decoder
3. Run the program:
   python encoder_decoder.py

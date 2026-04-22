# Morse Code Project in Python
A simple yet efficient Python-based Morse Code Translator that can convert English text into Morse code and decode Morse code back into English. This project focuses on dictionary mapping and string manipulation techniques in Python.

## 🚀 Features
Text to Morse: Convert English strings (letters, numbers, and basic punctuation) into their Morse code equivalent.

Morse to Text: Decode Morse code sequences back into readable English.

Clean Dictionary Mapping: Uses a structured dictionary for the International Morse Code standards.

Error Handling: Gracefully handles characters that are not supported in Morse code.

## 🛠️ How It Works
Morse code is a method used in telecommunications to encode text characters as standardized sequences of two different signal durations, called dots (.) and dashes (-).

## Logic:
Encoding: The program traverses the input string and replaces each character with its corresponding value from a predefined dictionary.

Decoding: The program splits the Morse string by spaces and performs a reverse lookup on the dictionary to find the original character.

## 💻 Usage
Once the script is executed, follow the on-screen prompts to select your mode:

1. Encrypt (Text to Morse)
Input: HELLO WORLD

Output: .... . .-.. .-.. --- / .-- --- .-. .-.. -..

2. Decrypt (Morse to Text)
Input: .... . .-.. .-.. ---

Output: HELLO

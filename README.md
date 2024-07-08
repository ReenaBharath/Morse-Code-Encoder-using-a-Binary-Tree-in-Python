# Morse Code Binary Tree

## Overview

This project implements a Morse code converter using a binary tree data structure. It supports both encoding plaintext messages into Morse code and decoding Morse code back into plaintext.

## Features

- **Encoding**: Converts plaintext messages to Morse code.
- **Decoding**: Converts Morse code messages back to plaintext.
- **Binary Tree Visualization**: Visualizes the binary tree used for Morse code conversion.

## Binary Tree Structure

The binary tree is structured to include the first four levels, which are sufficient to encode all 26 letters of the alphabet.

## Getting Started

### Prerequisites

- Python 3.x

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/morse-code-binary-tree.git
   ```
2. Navigate to the project directory:
   ```sh
   cd morse-code-binary-tree
   ```

### Running the Program

Run the `main.py` script to start the Morse code converter:
```sh
python main.py
```

## Usage

### Encoding

1. When prompted, choose to encode a message by entering `E`.
2. Enter your message (e.g., `SOS`).
3. The program will output the Morse code equivalent of your message.

### Decoding

1. When prompted, choose to decode a message by entering `D`.
2. Enter your Morse code message, using spaces to separate each Morse code character (e.g., `... --- ...` for `SOS`).
3. The program will output the decoded plaintext message.

### Example

```
Do you want to (E)ncode or (D)ecode a message? (E/D): E
Enter a message to convert into Morse Code: (e.g. SOS): SOS
Morse Code:
... --- ...

Do you want to (E)ncode or (D)ecode a message? (E/D): D
Enter a Morse Code message to decode (use space to separate letters): ... --- ...
Decoded Message:
SOS
```

## Files

- `main.py`: The main program file containing the Morse code conversion logic.
- `tree.py`: Contains the code to draw the binary tree structure.

## How It Works

### Encoding

1. The program constructs a binary tree where each node represents a character.
2. It traverses the tree to find the corresponding Morse code for each character in the input message.

### Decoding

1. The program reads the Morse code input.
2. It traverses the binary tree based on the sequence of dots and dashes to find the corresponding character.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

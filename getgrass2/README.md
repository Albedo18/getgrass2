# getgrass2

This repository contains the code for `getgrass2`, a bot designed to establish WebSocket connections through various HTTP and SOCKS proxies, specifically aimed at farming for Grass Airdrop Season 2.

## Overview

`getgrass2` connects to a specified WebSocket server using both HTTP and SOCKS proxies. It leverages the `ws` library for WebSocket communication and integrates the `https-proxy-agent` and `socks-proxy-agent` libraries for enhanced proxy support. This allows for more versatile and resilient connections, accommodating a wider range of proxy types.

## Installation

** Termux reposity, copy this command to your Termux on Android or IOS

   ```bash
   pkg install
   ```
   ```bash
   pkg install nodejs
   ```
   ```bash
   pkg update
   ```
   ```bash
   pkg upgrade
   ```
   ```bash
   pkg install git
   ```

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Madkalex/getgrass2.git
   ```

2. Navigate to the project directory:

   ```bash
   cd getgrass2
   ```

3. Install the required dependencies using npm:

   ```bash
   npm install
   ```

## Usage

1. Obtain your user ID from the Getgrass website:

   - Visit [https://app.getgrass.io/dashboard](https://app.getgrass.io/register/?referralCode=6ACtNYTict4Qugb).
   - Open your browser's developer tools (usually by pressing F12 or right-clicking and selecting "Inspect").
   - Go to the "Console" tab.
   - Paste the following command and press Enter:

     ```javascript
     localStorage.getItem('userId');
     ```

   - Copy the value returned, which is your user ID.

2. Create a file named `uid.txt` in the project directory and list your user IDs, each on a new line, like so:

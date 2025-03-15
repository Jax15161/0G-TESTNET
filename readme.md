# 0g Testnet auto tx

for auto swap 0g testnet

## Features

- Multi Account
- Support Proxy
- Swap USDT/ETH
- Swap ETH/USDT
- Swap USDT/BTC
- Swap BTC/USDT

## Requirements

- NodeJS [Download](https://nodejs.org/en/download).
- 0g Tesnet [Here](https://hub.0g.ai/portfolio/token).
- 0g Faucet [Here](https://hub.0g.ai/faucet)
- Proxy (Optional).

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/ahlulmukh/0g-bot.git
   cd 0g-bot
   ```

2. Instal Packages and build packages:

   ```sh
   npm install
   npm run build
   ```

3. Create a `proxy.txt` file in the root directory and add your proxies (one per line) (Optional).

   ```
   http://user:pass@host:port
   http://user:pass@host:port
   http://user:pass@host:port
   ```

4. Create privatekey `nano privatekey.txt` and put your private key one per line

   ```
   0xprivatkey1
   0xprivatkey2
   0xprivatkey3
   0xprivatkey4
   ```

## Usage

1. Run the bot:

```sh
npm run start
```

## Donation

If you would like to support the development of this project, you can make a donation using the following addresses:

- Solana: `5jQMndHzWVH8MCitXdUEYmshJZXVKCzUG12mxJku4WdX`
- EVM: `0x9688574cf1481950ae6201cbe5f6a9ae5a97cedd`
- BTC: `bc1ppfl3w3l4spnda7lawlhlycwuq2ekz74c936c8emwfprfu9hyun6sq5k6xl`

## Disclaimer

This tool is for educational purposes only. Use it at your own risk.

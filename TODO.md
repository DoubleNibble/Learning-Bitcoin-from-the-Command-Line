# TODOs

This is a list of potential (or planned) TODO items for "Learning Bitcoin from the Command Line". Many are drawn from issues found at the previous locale of this repo.

## 1. Add BTCDEB Support

Per @ChristopherA:

> @kallewoof has written a better Bitcoin Script debugging tool at https://github.com/kallewoof/btcdeb — we should re-write chapter 7 to use it.

`btcdeb -v` will now show you what BTC Core version it's based on in its minor version. As of now it's `0.2.19`, which is BTC Core 0.19.

## 2. Update Setup Instructions & Script to Debian 10

Per @matthiasdebernardini, our current script no longer works.

## 3. Upgrade to 0.19.1

We need to upgrade the whole tutorial to the newest BitCoin Core, and that means walking through it entirely, making sure it works, and redoing an examples with different output.

## 4. Fix BTCBlock for Testnet

The `btcblock` for testnet alias has had constant issues with the URLs delivering us total blockcounts for testnet going away. I'm not currently aware of any that work.

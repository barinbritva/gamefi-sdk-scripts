# gamefi-sdk-scripts

The tool is designed to help developers to setup games to use [GameFi SDK](https://github.com/ton-community/gamefi-sdk).

## Usage

Install the package and setup the environment for your project in the first place:

```bash
npm install -g gamefi-sdk-scripts
cd your-game-path
gamefi-sdk-scripts setup-env
```

Now you are ready to use the tool depending on your needs. See the command list below.

## Commands

`gamefi-sdk-scripts COMMAND` where `COMMAND` is one of:

| Command | Description |
| --- | --- |
| `setup-env` | Setup the environment for your project. |
| `deploy-jetton` | Deploy the jetton contract. |
| `deploy-nft-collection` | Deploy the NFT collection contract. |
| `get-wallet-state` | Get the wallet state. |
| `mint-jetton` | Mint jetton to the wallet. |
| `mint-nft` | Mint NFT to the wallet. |
| `transfer-jetton` | Transfer jetton to the wallet. |
| `transfer-nft` | Transfer NFT to the wallet. |

## License

[MIT](./LICENSE)

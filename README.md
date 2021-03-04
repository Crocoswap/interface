# Pangolin Interface

An open source interface for Crocoswap -- a community-driven decentralized exchange for Fantom assets with fast settlement, low transaction fees, and a democratic distribution -- powered by Fantom.

- Website: [crocoswap.org](https://crocoswap.org/)
- Telegram: [Crocoswap](https://t.me/Crocoswap)
- Twitter: [@Crocoswap](https://twitter.com/crocoswap)
- Medium: [Crocoswap](https://medium.com/@Crocoswap)


## Accessing the Crocoswap Interface

Visit [crocoswap.org](https://crocoswap.org).

## Development

### Install Dependencies

```bash
yarn
```

### Run

```bash
yarn start
```

### Configuring the environment (optional)

To have the interface default to a different network when a wallet is not connected:

1. Make a copy of `.env` named `.env.local`
2. Change `REACT_APP_NETWORK_ID` to `"{YOUR_NETWORK_ID}"`
3. Change `REACT_APP_NETWORK_URL` to your JSON-RPC provider 

Note that the interface only works on testnets where both 
[Pangolin](https://github.com/pangolindex/exchange-contracts) and 
[multicall](https://github.com/makerdao/multicall) are deployed.
The interface will not work on other networks.

## Attribution
This code was adapted from this Uniswap repo: [uniswap-interface](https://github.com/Uniswap/uniswap-interface).

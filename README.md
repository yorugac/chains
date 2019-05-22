# EVM-based Chains

Listed by chainId according to EIP-155

Data source available on `_data/chains.json`

## Example

```json
{
  "name": "Ethereum Mainnet",
  "shortName": "eth",
  "chain": "ETH",
  "network": "mainnet",
  "chainId": 1,
  "networkId": 1,
  "rpc": [
    "https://mainnet.infura.io/v3/${INFURA_API_KEY}",
    "https://api.mycryptoapi.com/eth"
  ],
  "faucets": [],
  "infoURL": "https://ethereum.org",
  "nativeCurrency": {"name":"Ether","symbol":"ETH","decimals":18}
}
```

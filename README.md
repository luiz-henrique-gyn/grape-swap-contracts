# grape-swap-contracts
Core smart contracts of Grape Swap

## Local Development
  
### Local Development Setup
1. Ganache
```bash
sudo npm install -g ganache-cli
```

2. Truffle
```bash
sudo npm install -g truffle
```

3. truffle-config.js development parameter:
```bash
development: {
    host: "127.0.0.1",
    port: 8545,
    network_id: "*"
}
``` 

### Local Development Build
1. In a separate termianl
```bash
ganache-cli
``` 

2. Contract compile

```bash
truffle compile
```
 
3. Contract Deploy
```bash
truffle migrate --reset
```  

## Production
Deploy and publish in Remix https://remix.ethereum.org/

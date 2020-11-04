# KSM PENDING PAYOUTS SUBMISSION
https://gitcoin.co/issue/Polkadot-Network/hello-world-by-polkadot/5/100023931

1) Clone https://github.com/paritytech/substrate-api-sidecar
2) cd substrate-api-sidecar
2) Create ```.env.kusama``` File with ```SAS_SUBSTRATE_WS_URL=wss://kusama-rpc.polkadot.io```
3) yarn install
4) NODE_ENV=kusama yarn start

5) python3 get_payouts.py [-a <address>] [-d <depth>] [-e <era>]
  
## Kusama Node Launch - TOO LONG TO WAIT FOR FULL SYNC, so I connected to a public node for testing

![alt text](https://github.com/tonysun83/substrate-account-payouts/blob/main/launchkusamanode.png?raw=true)

## Launching Side Car that connects to public node

![alt text](https://github.com/tonysun83/substrate-account-payouts/blob/main/launchsidecar.png?raw=true)

## Example Usage 1

![alt text](https://github.com/tonysun83/substrate-account-payouts/blob/main/payoutex1.png?raw=true)

## Example Usage 2


![alt text](https://github.com/tonysun83/substrate-account-payouts/blob/main/payoutex2.png?raw=true)

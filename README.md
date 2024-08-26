# KCC node client on Akash

## Deploy on Akash
Deploy KuCoin Community Chain (KCC) node client on Akash with YAML file in this repository.

## Node Sync
Check syncing status with RPC request below.
```
curl http://localhost:8545 \
  -X POST \
  -H "Content-Type: application/json" \
  -d '{"jsonrpc":"2.0","method":"eth_syncing","params": [],"id":1}'
```

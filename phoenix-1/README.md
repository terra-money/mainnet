## Phoenix-1

This repository provides genesis data for Terra 2.0.

### How to get genesis.json

```sh
wget https://phoenix-genesis.s3.us-west-1.amazonaws.com/genesis.json
mv ./genesis.json ~/.terra/config/genesis.json
jq -S -c -M '' ~/.terra/config/genesis.json | shasum -a 256
01788640307843f2b9b1759a832f5d8fa96ddeeab70d773f7c65ba0d629e8aef  -
```

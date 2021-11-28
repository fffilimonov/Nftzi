# Nftzi

# Deploy smart contract

cp .env.example .env

docker run -v `pwd`:/root/.celo --rm -it us.gcr.io/celo-org/geth:alfajores account new

update .env with retreived ADDRESS and PASSWORD

node getKey.mjs

update .env with retreived PRIVATE_KEY

open https://celo.org/developers/faucet and send coins to ADDRESS

./node_modules/.bin/truffle compile

./node_modules/.bin/truffle migrate --network alfajores


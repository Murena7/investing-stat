# Investing Stat

## Build & Run
### Prerequisites
- go 1.15
- docker

if necessary create block_number file and add there start block number.

Create .env file in root directory and add following values:
```dotenv
DB_DSN=postgres://localhost/dexeinvest2?sslmode=disable
DB_HOST=localhost
DB_PORT=5432
DB_USER=postgres
DB_PASSWORD=postgres
DB_DBNAME=dexeinvest2
DB_DIALECT=postgres
DB_MAX_OPEN-CONNS=80
ZAP_LEVEL=2
ETH_NODE=ws://localhost:8545
DEX_PROTOCOL=uniswapV2
DEX_FACTORY_ADDRESS=0x1187D2f98C556a3Cfbb270Be161EbB34EcD2925F
MAX_PARALLEL_BLOCKS=100
DB_DEBUG=true
NETWORK=bsc
```
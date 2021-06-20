# OhMiner - A Highly Optimized NVIDIA GPU Miner for Ethereum

```diff
+===================================================================
- ,-----. ,--.           .--,,--.   ,--.,--.                       
 '  .-.  '|  ,---.   .--'  / |   `.'   |`--',--,--,   ,---. ,--.--. 
-|  | |  ||  .-.  | /  ---`  |  |'.'|  |,--.|      \\ | .-. :|  .--'
 '  '-'  '|  | |  |`--'      |  |   |  ||  ||  ||  | \\   --.|  |   
- `-----' `--' `--'          `--'   `--'`--'`--''--'  `----'`--'    
+===================================================================
```

## Overview
OhMiner is a highly optimized cryptocurrency mining software. Comparing with other tools that are versatile, OhMiner is more concentrated. It aims to optimize Ethash for every single model of GPUs to achieve the best performance.

It takes weeks for our developers to fine tune the GPU kernel. Currently, we are thrilled to announce we have the best performance on the following GPU models. 

- RTX3090       🆙 3-5 MH/s higher than other tools (3~5% improvement)

  🔥**achieving nearly theoretical upper limit at 106Mh/s**
- Other RTX30xx 🆙 1-3 MH/s higher than other tools

  ✅**close to upper limit**

- RTX2080Ti 🆙 0.3-1 MH/s higher than other tools

  ✅**highly optimized**

🍻 Developer fee is 0.8%

[**Download**](https://github.com/OhMiner/OhMiner/releases)


## Usage

OhMiner uses the same interface as [Ethminer](https://github.com/ethereum-mining/ethminer/), please take a look of the following pages for details

[Example](https://github.com/ethereum-mining/ethminer/blob/master/docs/POOL_EXAMPLES_ETH.md)

#### quick examples

```
./ohminer -U -P scheme://EthWallet.worker1@PoolHostname:port
```

```
./ohminer -U -P stratum://0xasdfasdfasdfasdfasdfasdf.worker0@asia1.ethermine.org:14444
```

## F.A.Q

**OhMiner reports error:**
```
Error: locale::facet::_S_create_c_locale name not valid
```

Run these in your terminal and try again
```
export LC_ALL="en.utf-8"
export LC_ALL=C; unset LANGUAGE
```

## Requests and Bug Reports
Please feel free to open https://github.com/OhMiner/OhMiner/issues

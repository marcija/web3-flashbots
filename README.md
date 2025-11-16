# web3-flashbots
This library extends Web3.py by adding flashbots functionality as a module, enabling direct submission of transaction bundles to block builders. It implements middleware to intercept `eth_sendBundle` and `eth_callBundle` calls, routing them to your specified MEV-compatible RPC endpoint.

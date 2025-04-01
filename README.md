# Thetiswallet

Thetiswallet v1.0.0 – OTR Genesis Testnet

We’re excited to announce the first public release of Thetiswallet, the native CLI and infrastructure layer for the OTR (Over The Airwaves) Token built on a custom Cosmos-SDK blockchain.

Highlights
   •   Genesis Chain Bootstrapped
Custom genesis configuration loaded with testnet allocations for trike357, OTR ecosystem, airdrop, and node incentive accounts.
   •   Simulated Daemon (thetisd)
The core daemon (thetisd) has been compiled and validated, capable of producing blocks and creating validators.
   •   Key Management
Wallet keys added and balances preloaded for development testing and RPC-based transactions.
   •   RPC and Tendermint API Live
Accessible at localhost:26657 with validator info, consensus state, and block data endpoints exposed.
   •   Basic Transaction Signing Script
Includes a Python script (send_otr_tx.py) for signing and broadcasting transactions with a base64-encoded SECP256k1 private key.

File Structure
   •   thetisd – Compiled binary
   •   genesis.json – Custom testnet genesis
   •   cmd/ – Command-line build folder
   •   README.md, go.mod, and Makefile

How to Run

./thetisd start --home ~/.thetisd

Coming Soon
   •   Wallet GUI and OpenHPSDR integration
   •   Token faucet and Airdrop registration
   •   Mainnet deployment

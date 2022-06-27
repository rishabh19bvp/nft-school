# Lazy Minting

An example Solidity contract for "buyer pays" minting at the time of first sale.

This directory contains example code written for the [Lazy Minting guide on NFT School](https://nftschool.dev/how-to/lazy-minting/). See the full article for context and details on how everything works!

The basic gist is that the gas cost to mint an NFT is pushed onto the buyer as part of the first sale transaction. This works by having the NFT creator sign a "voucher" containing the data that will be recorded into the blockchain when the NFT is minted.

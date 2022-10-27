---
layout: post
type: socratic
title: "Socratic Seminar 7"
meetup: https://www.meetup.com/tampa-bay-bitcoin/events/sdcpxsydcpbfb/
---

## Taro!
* [Taro Docs](https://docs.lightning.engineering/the-lightning-network/taro/taro-protocol)
* [Taro GitHub](https://github.com/lightninglabs/taro/)
* [LND GitHub](https://github.com/lightningnetwork/lnd)
* Taro Playground - `ssh root@165.227.98.125`
* [Anigma (nostr messenger)](https://anigma.io/)
   * Channel ID - 3ff2cffa8931bd5d0a00fcfaa1do25262f97c085b97d3ce6aad04ac20cd0c6f4a
### Commands for the workshop
   * Open the taro workstation      `tmux attach-session -t taro<num>`
   * Move around terminals          `CTL + B -> o`
   * Generate block                 `bc -generate <num blocks>`
   * Send bitcoin to address        `bc snedtoaddress <address> <amount>
   * Get LND address                `lncli-<num> newaddress p2tr`
   * Start LND                      `taro-lnd-<num>`
   * LND command                    `lncli-<num>`
   * Start taro                     `tarod-<num>`
   * taro command                   `tarocli-<num>`  


# FYDCoin Masternode Setup Guide

wget -q https://raw.githubusercontent.com/Fydcoin/Masternode_Script/master/mninstall.sh

sudo chmod +x mninstall.sh

./mninstall.sh

When prompted to Enter your FYDCoin Masternode GEN Key.

Paster your Masternode GEN Key and press enter

Wait till Node is fully Synced with blockchain. For check enter below command.

fyd-cli getinfo

When Node Fully Synced enter below command for check masternode status.

fyd-cli masternode status
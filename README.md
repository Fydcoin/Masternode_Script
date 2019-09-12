# FYDCoin Masternode Setup Guide

## Step 1

Enter in your server command prompt:
```sh
wget -q https://raw.githubusercontent.com/Fydcoin/Masternode_Script/master/mninstall.sh
```

```sh
sudo chmod +x mninstall.sh
```

```sh
./mninstall.sh
```

## Step 2

When prompted to Enter your FYDCoin Masternode GEN Key.

Paster your Masternode GEN Key and press enter

# Verify node status

Wait until your masternode is fully Synced with blockchain. You can check this with the command below

```sh
fyd-cli getinfo
```

When your masternode is fully synced enter the command below to verify your masternode status.

```sh
fyd-cli masternode status
```

# Danom Early Worker Nodes (Mining) 
- Buy VPS di : [t.me/skuycloud](t.me/skuycloud)
- Trakteer buat buy Kopi : https://trakteer.id/brrrskuy/tip `<---`
-----------------
- First Create Account : https://huggingface.co/join

`Update system`
```
sudo apt update && sudo apt install -y wget curl tar screen
```
`Paste script to VPS`
```
wget https://github.com/DanomSite/release/releases/download/v4/DanomV4.tar.gz && tar -xvzf DanomV4.tar.gz
cd Danom
```
`Install`
```
curl -fsSL 'https://testnet.danom.site/install.sh' | bash
```
`0xYOUR_WALLET_ADDRESS = Change to your Wallet` 
`YOUR_POOL_LIST = Change to your API Huggingface`
```
echo '{"wallet": "0xYOUR_WALLET_ADDRESS", "pool_list": "YOUR_POOL_LIST"}' > wallet_config.json
```
`Create Screen`
```
screen -S danom
```
`Run Script`
```
./danom
```
`CTRL+A+D` to back home again and save 

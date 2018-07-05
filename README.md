# Monkeytips-Blockchain-Explorer
Block explorer for Monkeytips CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon monkeytipsd. It should be accessible from the Internet. Run monkeytipsd with open port as follows:
```bash
./monkeytipsd --enable-cors="*" --enable_blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=13002
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.


### Development
Donate: Don't donate.  

### Note

All of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer & turtlecoin/block-explorer

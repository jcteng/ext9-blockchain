# N-Chain Project Ext9

Thanks to the outstanding work accomplished by Chia, it is possible to run multiple blockchain projects using the same hardware resources. Multiple blockchains running simultaneously on PosT based projects can record more consensus data-blocks without causing a waste of social resources.

Ext9 is designed precisely for co-farming with chia to share the same plots serve for more consensus data.it also will be the best testing ground for Chialisp.

## install 

### windows

download last binnary from https://ext9.org/download/binary/
execute installer .

### linux from source 
```bash 
git clone https://github.com/ext9/ext9-blockchain.git -b net9.dev  --recurse-submodules
cd ext9-blockchain
sh install.sh
. ./activate
```

### ubuntu deb
```bash
wget https://ext9.org/download/binary/0.0.62/nchainext9-blockchain_0.0.63.dev0_amd64.deb
sudo dpkg -i nchainext9-blockchain_0.0.63.dev0_amd64.deb
sudo apt install -f

/usr/lib/nchainext9-blockchain/resources/app.asar.unpacked/daemon/chia start farmer
```


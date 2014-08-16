
Copyright (c) 2013-2014 HaloCoin Developers


HaloCoin 0.3.0 BETA

Copyright (c) 2013-2014 HaloCoin Developers
Copyright (c) 2013 NovaCoin Developers
Copyright (c) 2011-2012 Bitcoin Developers
Distributed under the MIT/X11 software license, see the accompanying
file license.txt or http://www.opensource.org/licenses/mit-license.php.
This product includes software developed by the OpenSSL Project for use in
the OpenSSL Toolkit (http://www.openssl.org/).  This product includes
cryptographic software written by Eric Young (eay@cryptsoft.com).


Intro
-----
HaloCoin is a free open source project derived from NovaCoin, with
the goal of providing a long-term energy-efficient scrypt-based crypto-currency.
Built on the foundation of Bitcoin and NovaCoin, innovations such as proof-of-stake
help further advance the field of crypto-currency.

Setup
-----
After completing windows setup then run windows command line (cmd)
  cd daemon
  HaloCoind
You would need to create a configuration file HaloCoin.conf in the default
wallet directory. Grant access to HaloCoind.exe in anti-virus and firewall
applications if necessary.

The software automatically finds other nodes to connect to.  You can
enable Universal Plug and Play (UPnP) with your router/firewall
or forward port 12788 (TCP) to your computer so you can receive
incoming connections.  HaloCoin works without incoming connections,
but allowing incoming connections helps the HaloCoin network.

Upgrade
-------
All you existing coins/transactions should be intact with the upgrade.
To upgrade first backup wallet
HaloCoind backupwallet <destination_backup_file>
Then shutdown HaloCoind by
HaloCoind stop
Start up the new HaloCoind.


See the documentation/wiki at the HaloCoin site:
  http://HaloCoin.cc/
for help and more information.


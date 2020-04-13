Cadcoin 
=======

Copyright (c) 2009-2014 Bitcoin Developers

Copyright (c) 2011-2014 Cadcoin Developers

Copyright (c) 2020-2020 Cadcoin Developers


What is Cadcoin?
----------------

Cadcoin is a lite version of Litecoin using scrypt as a proof-of-work algorithm.
 - 5 minute block targets
 - subsidy halves in 750k blocks
 - ~6 million total coins
 - 50 coins per block

What is next?
-------------

windows wallet and mining client.✔✔

https://github.com/cadcoin-project/windows-miner-client.git

Nodes.

2 nodes up and running added in pseed in net.cpp script.✔✔

website.

not yet.

Block explorer.✔✔

http://45.76.42.141:3001/


mining pool.

not yet


current info.
-------------

coins mined to date 216700

blocks mined to date 4334

network speed 467MH

difficulty 15

-------------------------------------------------------------------------------------------------------------------------

Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./cadcoin-qt_test

# cadcoin team


# DUELIUM
https://DUELIUM.io  // coming soon

https://DUELIUM.com // OLD-concept

DUELIUM is a privacy focused MN/PoS coin, iteratively improved with the most advanced technological features.
DUELIUM is 100% community governed and built. Every move is community-driven, as DUELIUM technology includes a decentralized budgeting system and immutable proposal and voting systems.

## MANIFESTO ##

DUELIUM was created as an answer to two issues : lack of privacy and lack of decentralization. Its purpose is to become a staple medium of exchange, 100% private and decentralized, linking up several applications, all of them built by the community, for the community.
In the first phase, DUELIUM holders benefit from a superior incentive for holding, such a feature was purposely designed to ensure maximum network security, decentralization and early adopter engagement. This phase will last 104 days until MN holders will vote for the best proposals concerning DL economics and applications for phase 2 through DL technical vote feature.
However, the core team plans to deliver a fully integrated P2P marketplace for 2019 called DLMarket, regardless of future applications.

## BITCOINTALK ##

https://bitcointalk.org/index.php?topic=4742873.0  // OLD

## COINS SPECS ##

Ticker: DL

Supply Cap: 8,888,888 DL

Premine: 685,500 (Public Swap Only)

Type: POW until block 350 | POS/MN thereafter

Masternode collateral: 20,000 DL until block 200,000

                       50,000 DL after block 200,000

Masternode Rewards: 90% of the block reward until 400,000

                    95% of the block reward after 400,000

Stake Rewards: 10% of the block reward until 400,000
                
                5% of the block reward after 400,000  

P2P port: 9888 | RPC port: 9889

Algo: Quark-hash (+zPoS v3.0)

Block Time: 60 Seconds

Difficulty Retarget: Every Block

Privacy: Zerocoin | DAO: Masternode vote


## ADDNODE ##

addnode=144.202.124.63

addnode=108.61.219.8

addnode=149.248.5.66

addnode=45.32.82.96 

addnode=108.61.216.144


## COMPILE NOTE ##

chmod u+x share/genbuild.sh

chmod u+x src/leveldb/build_detect_platform

chmod u+x ./autogen.sh && ./autogen.sh

./configure --disable-dependency-tracking --enable-tests=no --without-gui --without-miniupnpc

make

make install

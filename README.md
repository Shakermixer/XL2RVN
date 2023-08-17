About The Site
 17th August 2023 at 2:08pm
This site is running with TiddlyWiki, one of the most versatile ENVIRONMENTS i know of.

https://github.com/Jermolene/TiddlyWiki5

https://tiddlywiki.com/

Arbitrum
 17th August 2023 at 2:12pm
Arbitrum is an optimistic rollup scaling solution, combining multiple transactions into one smart contract message for bulk processing on Ethereum.

Branding
 17th August 2023 at 7:06pm
Logo

Ethereum
 16th August 2023 at 6:51pm
Ethereum
Smart contract platform on a L1 blockchain which shifted recently from PoW to PoS with underlying token called Ether.

The underlying EVM represents a shared state machine with Turing Completeness that consumes opcodes, which can be compiled from Solidity or Vyper.

Fantom
 17th August 2023 at 3:51pm
Fantom is a fast, high-throughput open-source smart contract platform for digital assets and dApps.

https://fantom.foundation/get-started/

GETH
 17th August 2023 at 2:07pm
Official Golang execution layer implementation of the Ethereum protocol.

Hashing Algorithms
 17th August 2023 at 5:50pm
Secure Hash Algorithms:

SHA-0: A retronym applied to the original version of the 160-bit hash function published in 1993 under the name "SHA". It was withdrawn shortly after publication due to an undisclosed "significant flaw" and replaced by the slightly revised version SHA-1.
SHA-1: A 160-bit hash function which resembles the earlier MD5 algorithm. This was designed by the National Security Agency (NSA) to be part of the Digital Signature Algorithm. Cryptographic weaknesses were discovered in SHA-1, and the standard was no longer approved for most cryptographic uses after 2010.
SHA-2: A family of two similar hash functions, with different block sizes, known as SHA-256 and SHA-512. They differ in the word size; SHA-256 uses 32-bit words where SHA-512 uses 64-bit words. There are also truncated versions of each standard, known as SHA-224, SHA-384, SHA-512/224 and SHA-512/256. These were also designed by the NSA.
SHA-3: A hash function formerly called Keccak, chosen in 2012 after a public competition among non-NSA designers. It supports the same hash lengths as SHA-2, and its internal structure differs significantly from the rest of the SHA family.
The corresponding standards are FIPS PUB 180 (original SHA), FIPS PUB 180-1 (SHA-1), FIPS PUB 180-2 (SHA-1, SHA-256, SHA-384, and SHA-512). NIST has updated Draft FIPS Publication 202, SHA-3 Standard separate from the Secure Hash Standard (SHS).

Important: !!! KECCAK (This has to be thouroughly studied a few times and implemented) e.g. https://pkg.go.dev/golang.org/x/crypto/sha3?utm_source=godoc

reading here: https://en.wikipedia.org/wiki/SHA-3

High Level Perspective (Terminology):
 15th August 2023 at 12:57pm
Ethereum

Smart contract platform on a L1 blockchain which shifted recently from PoW to PoS with underlying token called Ether.

The underlying EVM represents a shared state machine that consumes opcodes, which can be compiled from Solidity or Vyper.

Geth

Official Golang execution layer implementation of the Ethereum protocol.

https://github.com/ethereum/go-ethereum

Several forks exist aside from the official one, like:

https://github.com/OffchainLabs/go-ethereum

How could Xen, XenNFT and the derivatives like DBXen, Fenix, XenDoge and others be brought/used on the Ravencoin Rlockchain?
 13th August 2023 at 11:26pm
This question is the motivation of this repo.

The README is the primary container for text to collect, to describe concepts, which are needed, useful or help. Feel free to contribute.

Yeeehaw.

Layer1
 16th August 2023 at 7:00pm
Layer1 refers to a base network, such as Bitcoin, BNB Chain, Ethereum or Ravencoin and its underlying infrastructure. Layer1 blockchains can validate and finalize transactions without the need for another network. Making improvements to the scalability of layer-1 networks is difficult, as we’ve seen with Bitcoin. As a solution, developers create layer-2 protocols that rely on the layer-1 network for security and consensus. Bitcoin's Lightning Network is one example of a layer-2 protocol. It allows users to make transactions freely before recording them into the main chain.

Layer2
 16th August 2023 at 7:04pm
Layer2 refers to any off-chain network, system, or technology built on top of a blockchain (commonly known as a Layer1 network) that helps extend the capabilities of the underlying base layer network. Layer2 networks can support any blockchain to introduce enhancements such as higher transaction throughputs. In regards of this repo, the main motivation is to achieve a special EVM functionality, which enables the use of the XEN Cryptocurrency and it's derivatives. The Ravencoin Chain is very fast and not expensive at all.

Miners
 17th August 2023 at 6:04pm
I only list open source without fee miners for linux, easier for my monkey brain:

KAPOW
https://github.com/RavenCommunity/kawpowminer/releases

mines RVN.

Ethash
https://github.com/ethereum-mining/ethminer

mines ethash coins like ETHW,ETHF etc...

Mining Algorithms
 17th August 2023 at 4:02pm
KAPOW
KAWPOW is a mining algorithm mainly known thanks to Ravencoin. It also supports other cryptocurrencies, like Gravium, Hilux, as well as other less popular projects. The algorithm is protected against ASICs and potential centralization. In order to achieve this, the developers alternate between X15 and SHA51 algorithms. Their choice also depends on the hash of the previous block. The algorithm works well on graphics cards – you can use Teamredminer or Bminer for AMD cards and T-Rex or Gminer for Nvidia. In terms of mining on KAWPOW algorithm, “green” graphics cards are better. GTX 1080Ti and RTX 2080Ti hash rates are 1.5 times higher than those of Vega and Radeon VII. (Source: https://2cryptocalc.com/kawpow-algorithm)

https://ravencoin.org/assets/documents/X16R-Whitepaper.pdf

Ethash
Ethash is a heavyweight PoW algorithm used by the most popular cryptocurrencies, including Ethereum, as well as MOAC, Expanse, Pirl, etc. The algorithm is different, because it uses the DAG file that is loaded into GPU memory at the moment of miner launch. An epoch change takes place every 30000 blocks and leads to an increase in size of the DAG file by 8 MB.

Ethash cryptocurrencies are mined using NVIDIA and AMD graphics cards and also the ASIC miners. For Ethereum 3GB GPU memory is already not enough as it could not store the DAG file. 4GB or more GPU memory is required to mine ETH. Please note that the Ethereum network usually has a significant value of transaction fees included into each block. The calculator takes the average value of the transaction fees into account while calculating ETH mining profitability. (update: Ethereum transitiooned to PoS September 2022). (source:https://2cryptocalc.com/ethash-algorithm)

https://ethereum.org/en/developers/docs/consensus-mechanisms/pow/mining-algorithms/

Moonbeam
 17th August 2023 at 4:55pm
.... Moonbeam is much more than just an EVM implementation: it’s a highly specialized Layer 1 chain that mirrors Ethereum’s Web3 RPC, accounts, keys, subscriptions, logs, and more. The Moonbeam platform extends the base Ethereum feature set with additional features such as on-chain governance, staking, and cross-chain integrations. ....

source: https://moonbeam.network/

More info:

https://docs.moonbeam.network/

https://apps.moonbeam.network/moonbeam

Token Stats:

https://www.coingecko.com/en/coins/moonbeam

Neoxa
 17th August 2023 at 4:05pm
Neoxa is an innovative Proof of Work cryptocurrency that seamlessly merges the realms of gaming and cryptocurrency. With Neoxa, you no longer need to spend your time gaming for free; instead, you can harness the power of your gameplay to earn rewards that can be utilized for your in-game purchases and much more. (source: https://neoxa.net/)

New Excision
 16th August 2023 at 6:54pm
Ethereum

EVM
run-time environment for smart contracts. Very popular, because most Layer 2 networks and side chains are compatible with evm code. As a matter of fact, the dev tooling and deploying are nearly identical.

Geth
Official Golang execution layer implementation of the Ethereum protocol.

https://github.com/ethereum/go-ethereum

Several forks exist aside from the official one, like:

https://github.com/OffchainLabs/go-ethereum

Token Stats:
https://www.coingecko.com/en/coins/ethereum

https://coinmarketcap.com/currencies/ethereum/

New Tiddler
 14th August 2023 at 2:41am

Optimistic Rollups
 17th August 2023 at 12:03am
OR2023-08-16-23-51-34.png
 17th August 2023 at 12:00am

Polygon
 17th August 2023 at 3:10pm
Token Stats: https://coinmarketcap.com/currencies/matic/ https://www.coingecko.com/en/coins/matic

Rationale
 16th August 2023 at 7:09pm
Rationale
I am big fan of the XEN Crypto Eco and Ravencoin was the first i mined on a RTX 2070 in 2022! Somehow i had this crazy idea of XEN and it's derivatives on the Ravencoin blockchain. The principles incorporated in XEN & RVN aka Ravencoin deserve to be promoted in Crypto! That is what i think.

Ravencoin
 17th August 2023 at 1:27pm
is a peer-to-peer blockchain, handling the efficient creation and transfer of assets from one party to another. It's consensus mechanism is based on PoW in such way that no ASIC can be used to mine efficiently.

https://ravencoin.org/ https://ravencoin.org/assets/documents/Ravencoin.pdf https://raven.wiki/w/Ravencoin_Wiki https://github.com/RavenProject/Ravencoin

Token Stats:
https://coinmarketcap.com/currencies/ravencoin/ https://www.coingecko.com/en/coins/ravencoin

Ravencoin Docs
 17th August 2023 at 4:09pm
A place for Ravencoin Documentation:

https://ravencoin.org/assets/documents/Ravencoin.pdf

https://github.com/RavenProject/Ravencoin/blob/master/doc/README.md

rollups
 16th August 2023 at 11:58pm

Sidechain
 17th August 2023 at 1:30pm
A sidechain is a separate blockchain that runs independent of Ethereum and is connected to Ethereum Mainnet by a two-way bridge. Sidechains can have separate block parameters and consensus algorithms, which are often designed for efficient processing of transactions. Using a sidechain involves trade-offs, though, as they do not inherit Ethereum's security properties. Unlike layer 2 scaling solutions, sidechains do not post state changes and transaction data back to Ethereum Mainnet.

Source: https://ethereum.org/en/developers/docs/scaling/sidechains/

Some fast ideas
 17th August 2023 at 6:00pm
Idea 1
A L2 to RVN with EVM functionality (input by BlackTron): Obviously the all inclusive, most complete solution. Could immensely aid the birb, because of the EVM functionalityy, which rules supreme in DEFI. (prove needed). Not very probable, that i alone can do it, but i might be not the only one, who likes to think on that stuff ...
The NFT contains the rXEN contract code and data as metadata, which is embedded in high level artwork, no smart contract is needed on the RVN side for minting NFTs. As embedded mirror.
User mints Ravencoin NFT by paying TX costs and exact minting costs, and initiates an contract call to (X1 Fastnet). All (100%) of what the user pays, is used to acquire mint contingent & Contract TX costs.
This contract call initiates checks, whether payment was done (read only), and then calls like Claim Bulk Rang from the XenNFT code by signaling through cross chain protocol.
On the date of claiming, user initiates claim from RVN side, this calls ClaimReward and releases rvXEN (or 1:1 Variant) which will be locked directly in a contract forever(!), which signals to the RVN side to release wrapped rXEN, in the exact amount locked.
Idea 2
Include in the metadata a minified evm interpreter, which can be injected in the DOM or vDom by similar mechanism, kind of #quine. Is that possible? Holding account? This concept might be especially fruitful, for exploring self hosting solutions connecting to blockchains, as well as this microkernel thing regarding ECMA, Vanilla ECMA, that is.
n.b. I pick up my other thoughts and more important, from others concerning this, but want to build crawler / spider specifically for that purpose first, to practice.

Task01
 17th August 2023 at 5:38pm
Task : Build a site with the updated content of the readme.md, delete the readme and export the site to readme.md on github, serve the site from there & mirror to Ravencoin IPFS!
How: Import the text manually or by plugin to form tiddlers, add navigation, create & check links
Status: nearly finished, just adding data & stuff.
Task02
 17th August 2023 at 5:09pm
Task: Develop an alternative interface for Uniswap swaps hosted or deployed on ipfs.
Motivation: In August 2023 Uniswap decided to block Hex Currency, one of a lot of turbulences, that followed the incarceration of Richard Heart. Jack L. (@mrjacklevin) mentioned, that the community should provide an alternative to call the contract code. I take this as a practice. Well knowing that one can access contract calls through Blockexplorer Interface.
Thinking loud in a social network
 17th August 2023 at 6:18pm
IDEA 1

A L2 to RVN with EVM functionality (input by BlackTron): Obviously the all inclusive, most complete solution. Could immensely aid the birb, because of the EVM functionalityy, which rules supreme in DEFI. (prove needed). Not very probable, that i alone can do it, but i might be not the only one, who likes to think on that stuff ...

The NFT contains the rXEN contract code and data as metadata, which is embedded in high level artwork, as no smart contract is needed on the RVN side for minting NFTs. As embedded mirror.
User mints Ravencoin NFT by paying TX costs and exact minting costs, and initiates an contract call to (X1 Fastnet). All (100%) of what the user pays, is used to acquire mint contingent & Contract TX costs.
This contract call initiates checks, whether payment was done (read only), and then calls like Claim Bulk Rang from the XenNFT code by signaling through cross chain protocol.
On the date of claiming, user initiates claim from RVN side, this calls ClaimReward and releases rvXEN (or 1:1 Variant) which will be locked directly in a contract forever(!), which can be read out from RVN side to release wrapped rXEN, in the exact amount locked.
IDEA 2

Include in the metadata a minified EVM interpreter, which can be injected in the DOM or vDom by similar mechanism, kind of #quine. Is that possible? Holding account? This concept might be especially fruitful, for exploring self hosting solutions connecting to blockchains, as well as this microkernel thing regarding ECMA, Vanilla ECMA, that is.

I pick up my other thoughts, but want to build crawler / spider specifically for that purpose first, to practice.

Thinking loud in a social network (X formerly known as Twitter)
 17th August 2023 at 6:10pm
fast ideas, that came nearly instantly, which might be rooted in the vast infinity of my ignorance:
Idea 1

A L2 to RVN with EVM functionality (input by BlackTron): Obviously the all inclusive, most complete solution. Could immensely aid the birb, because of the EVM functionalityy, which rules supreme in DEFI. (prove needed). Not very probable, that i alone can do it, but i might be not the only one, who likes to think on that stuff ...
The NFT contains the rXEN contract code and data as metadata, which is embedded in high level artwork, as no smart contract is needed on the #RVN side for minting NFTs. As embedded mirror.
User mints Ravencoin NFT by paying TX costs and exact minting costs, and initiates an contract call to (X1 Fastnet). All (100%) of what the user pays, is used to acquire mint contingent & Contract TX costs.
This contract call initiates checks, whether payment was done (read only), and then calls like Claim Bulk Rang from the XenNFT code by signaling through cross chain protocol.
On the date of claiming, user initiates claim from RVN side, this calls ClaimReward and releases rvXEN (or 1:1 Variant) which will be locked directly in a contract forever(!), which signals to the RVN side to release wrapped rXEN, in the exact amount locked.
Idea 2

Include in the metadata a minified evm interpreter, which can be injected in the DOM or vDom by similar mechanism, kind of #quine. Is that possible? Holding account? This concept might be especially fruitful, for exploring self hosting solutions connecting to blockchains, as well as this microkernel thing regarding ECMA, Vanilla ECMA, that is.
I pick up my other thoughts, but want to build crawler / spider specifically for that purpose first, to practice. fast ideas, that came nearly instantly, which might be rooted in the vast infinity of my ignorance:

This section is intended for live coding experiments
 17th August 2023 at 2:15pm
here goes editor
Untitled
 
New Tiddler 1

XEN
 16th August 2023 at 11:32pm
XEN is a universal cryptocurrency to achieve the original mission of Blockchain, following the Blockchain Tenets of

decentralization
transparency
counterparty risk resistance
peer-to-peer
value exchange
self-custody
Its unique tokenomics focuses on the mass market adoption with the lowest barrier to entry compared to the rest of coins on the market today.

https://github.com/FairCrypto/XEN-crypto

https://faircrypto.org/xencryptolp.pdf

https://xen.network/

https://github.com/FairCrypto

XL2RVN
 17th August 2023 at 7:07pm
A collection of Ideas to bring Xen to the Ravencoin Chain (very incomplete, at the beginning, daily updated)

How could Xen, XenNFT and the derivatives like DBXen, Fenix, XenDoge & XenShiba and others be brought/used on the Ravencoin Rlockchain?

This question is to be examined here. The site is the primary container for text to collect, to describe concepts, which are needed, useful or help. Feel free to contribute.

^^Yeeehaw.^^

Rationale

High Level Perspective (Terminology):
Ethereum

Fantom

Layer1

Layer2

Moonbeam

XEN

Neoxa

Optimistic Rollups

Ravencoin

Sidechain

zK-Rollups

Polygon

Deeper Dives and Concepts explained:
Ethereum

https://ethereum.org/en/developers/

Starting point for developing apps & contracts based on the EVM to be deployed on Ethereum.

Fantom

https://fantom.foundation/get-started/#for-developers

Starting point for developing apps & contracts based on the EVM to be deployed on Fantom.

Polygon

https://polygon.technology/developers

Starting point for developing apps & contracts based on the EVM to be deployed on Polygon.

Hashing Algorithms

Minining Algorithms

Ravencoin Docs

Tools of the Trade:
Miners

On a blockchain, mining is the validation of transactions. For this effort, successful miners obtain new cryptocurrency as a reward. The reward decreases transaction fees by creating a complementary incentive to contribute to the processing power of the network. The rate of generating hashes, which validate any transaction, has been increased by the use of specialized machines such as FPGAs and ASICs running complex hashing algorithms like SHA-256 and scrypt.[66] This arms race for cheaper-yet-efficient machines has existed since Bitcoin was introduced in 2009.[66] Mining is measured by hash rate typically in TH/s.

source:https://en.wikipedia.org/wiki/Cryptocurrency

Tech
A place for details, snippets and the low level stuff to master. I will add "Tasks" for me, which implementation aids step wise to acTask01hieve the necessary literacy in code and which i intend to use as building blocks. Obviously the hardest and the most rewarding part.

source code spotting:
This section is for selected source code study.

Tasks:
Task01 This is the active Task i am on right now.

Task02

Brainstorming & idea collecting
Thinking loud in a social network

Branding, PR & Marketing:
Branding

PR

Marketing

Media Coverage

Media Spending

Funding

zK-Rollups
 17th August 2023 at 1:34pm
ZK-rollups extend the throughput on Ethereum’s base layer by taking computation off-chain, but the real boost for scaling comes from compressing transaction data. Ethereum’s block size limits the data each block can hold and, by extension, the number of transactions processed per block. By compressing transaction-related data, ZK-rollups significantly increase the number of transactions processed per block.

ZK-rollups can compress transaction data better than optimistic rollups since they don't have to post all the data required to validate each transaction. They only have to post the minimal data required to rebuild the latest state of accounts and balances on the rollup.

Source: https://ethereum.org/en/developers/docs/scaling/zk-rollups/#scaling-ethereum-with-zk-rollups

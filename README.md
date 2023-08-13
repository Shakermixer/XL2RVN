# XL2RVN

## A collection of Ideas to bring Xen to the Ravencoin Chain


### How could Xen, XenNFT and the derivatives like DBXen, Fenix, XenDoge and others be brought/used on the Ravencoin Rlockchain? 
This question is the motivation of this repo.

The README is the primary container for text to collect, to describe concepts, which are needed, useful or help.
Feel free to contribute.

Yeeehaw.


### Rationale

I am big fan of the Xen Crypto Eco and Ravencoin was the first i mined on a RTX 2070 in 2022! 
Somehow i had this crazy idea of Xen and it's derivatives on the Ravencoin blockchain.
The principles incorporated in XEN & RVN deserve to be promoted in Crypto!
That is what i think.


### High Level Perspective (Definitions, Entities & Terminology):

#### Ethereum 

Smart contract platform on a L1 blockchain which shifted recently from PoW to PoS with underlying token called Ether. 

The underlying EVM represents a shared state machine that consumes opcodes, which can be compiled from Solidity or Vyper. 


##### Geth

Official Golang execution layer implementation of the Ethereum protocol.

https://github.com/ethereum/go-ethereum

Several forks exist aside from the official one, like:

https://github.com/OffchainLabs/go-ethereum

##### Token Stats:

https://www.coingecko.com/en/coins/ethereum

https://coinmarketcap.com/currencies/ethereum/


#### Layer 1 
refers to a base network, such as Bitcoin, BNB Chain, Ethereum or Ravencoin and its underlying infrastructure. Layer-1 blockchains can validate and finalize transactions without the need for another network. Making improvements to the scalability of layer-1 networks is difficult, as we’ve seen with Bitcoin. As a solution, developers create layer-2 protocols that rely on the layer-1 network for security and consensus. Bitcoin's Lightning Network is one example of a layer-2 protocol. It allows users to make transactions freely before recording them into the main chain.


#### Layer 2 
refers to any off-chain network, system, or technology built on top of a blockchain (commonly known as a layer-1 network) that helps extend the capabilities of the underlying base layer network. Layer-2 networks can support any blockchain to introduce enhancements such as higher transaction throughputs. In regards of this repo, the main motivation is to achieve a special EVM functionality, which enables the use of the XEN Cryptocurrency and it's derivatives. The Ravencoin Chain is very fast and not expensive at all.

#### EVM 
run-time environment for smart contracts. Very popular, because most Layer 2 networks and side chains are compatible with evm code. As a matter of fact, the dev tooling and deploying are nearly identical.  


#### XEN 
is a universal cryptocurrency to
achieve the original mission of Blockchain, following the Blockchain Tenets of
decentralization, transparency, counterparty risk resistance, peer-to-peer
value exchange and self-custody. Its unique tokenomics focuses on the mass
market adoption with the lowest barrier to entry compared to the rest of
coins on the market today.

https://github.com/FairCrypto/XEN-crypto

https://faircrypto.org/xencryptolp.pdf

https://xen.network/

https://github.com/FairCrypto

##### Ecosystem: 

Xen is deployed on the following chains:

* Avalanche:
  Contract:   aXen | 0xC0C5AA69Dbe4d6DDdfBc89c0957686ec60F24389
  
   
* Binance:
  Contract:   bXen | 0x2AB0e9e4eE70FFf1fB9D67031E44F6410170d00e
  
   
* Dogechain:
  Contract:    dcXen | 0x948eed4490833D526688fD1E5Ba0b9B35CD2c32e
  
   
* Ethereum:
  Contract:    Xen | 0x06450dEe7FD2Fb8E39061434BAbCFC05599a6Fb8
  
 
* Ethereum POW:
  Contract:    vvxen | 0x2AB0e9e4eE70FFf1fB9D67031E44F6410170d00e
  
   
* Evmos
  Contract:    coXen | 0x2AB0e9e4eE70FFf1fB9D67031E44F6410170d00e
  
  
* Fantom
  Contract:    fmXen | 0xf65D307365C19E07A9EaB7Fc8EaAB28600C8FA54
  
* Moonbeam
  Contract:    mbXen | 0xb564A5767A00Ee9075cAC561c427643286F8F4E1
  
 
* OKX Chain
  Contract:    okXen | 0x1cC4D981e897A3D2E7785093A648c0a75fAd0453
  
  
* Pulsechain:
  Contract:    pXen | 0x8a7FDcA264e87b6da72D000f22186B4403081A2a
  
   
* Polygon
  Contract:    mXen | 0x2AB0e9e4eE70FFf1fB9D67031E44F6410170d00e



#### Optimistic Rollup 
is a layer 2 or L2 scaling protocol normally tailored for extending the throughput associated with the base layer of Ethereum. In this case the goal would be to achieve EVM functionality with the base layer 1 being the Ravencoin Blockchain.


#### Ravencoin

is a peer-to-peer blockchain, handling the efficient creation and transfer of assets from one party to another. It's consensus mechanism is based on PoW

https://ravencoin.org/
https://ravencoin.org/assets/documents/Ravencoin.pdf
https://raven.wiki/w/Ravencoin_Wiki
https://github.com/RavenProject/Ravencoin

##### Token Stats:
https://coinmarketcap.com/currencies/ravencoin/
https://www.coingecko.com/en/coins/ravencoin



#### Sidechain
secondary blockchain with it's own consensus protocol. Prominent example is the Polygon chain.



<a title="Gentlejack35, CC BY-SA 4.0 &lt;https://creativecommons.org/licenses/by-sa/4.0&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Blockstream.jpg"><img width="512" alt="Blockstream" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e9/Blockstream.jpg/512px-Blockstream.jpg"></a>


#### zk-Rollups
Layer 2 blockchain solution that performs computations and storage off-chain while funds are held in a smart contract.
Prominent examples are Polygon zkEVM and zkSync Era.

#### Polygon 
has a very popular side chain with it's own consesus mechanism and it's own token MATIC


### Deeper Dive and Concepts explained:

#### Ethereum 
https://ethereum.org/en/developers/ starting point for devlopping apps & contracts based on EVM.

#### Minining Algorithms

https://ravencoin.org/assets/documents/X16R-Whitepaper.pdf

https://ethereum.org/en/developers/docs/consensus-mechanisms/pow/mining-algorithms/

#### Ravencoin Docs

https://ravencoin.org/assets/documents/Ravencoin.pdf

https://github.com/RavenProject/Ravencoin/blob/master/doc/README.md


### Tools of the Trade:

#### Miners:

https://github.com/RavenCommunity/kawpowminer/releases 
mines RVN.

https://github.com/ethereum-mining/ethminer
mines ethash coins like ETHW,ETHF etc...


### Tech

A place for details, snippets and the low level stuff to master 


### Possible Ways

* A L2 to RVN with EVM functionality (input by BlackTron)
  
* NFT contains the Xen contract code and data as metadata, as no smart contract is needed on the #RVN side for minting NFTs. This content can be interpreted by scripts and the NFTs are already tradable natively. With a #Xen token on #RVN, to hold account.
  
* Include in the metadata a minified evm interpreter, which can be injected in the DOM or by similar mechanism, kind of #quine. Is that possible?









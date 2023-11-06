# 1 - Introduction to Cryptocurrency

-> Cryptocurrency: are a form of decentralized digital money/currency Cryptocurrencies don't have a central issuing or regulating authority, instead  they use a decentralized system to record transactions and issue new units.

-> Fiat Currency: is government-issued currency that is not backed by a commodity such as gold. The US Dollar, Canadian  Dollar, Euro and various other currencies are all examples of fiat currency.

-> Cryptocurrency:

* Any form of currency that exists digitally or virtually and uses cryptography to secure transactions;
* Don't have a central issuing or regulationg authority;
* Use a decentralized system to record transactions and issue new units;
* Many different types of cryptocurrencies. Some are simply currencies while others can be considered platforms.

-> White Papers:

* A document released by developers that explains the technology and purpose of the project;
* Should define the following characteristis/properties:
    * Why the project was created;
    * The projects real-world utility;
    * Consensus mechanism;
    * Initial coin distribution;
    * Technical explanation (math, cryptography, formulas);
    * Timeline (ICO, releases).

-> Fiat Currency:

* Government issued currency that is not backed by a commodity sych as gold;
* Fiat currency gives central banks greater control over the economy because they can control circulation;
* Fiat money is backed only by the faith of the controlling government;
* Corrupt governments or poor monetary policy can cause hyperinflation and devalue currencies.


# 2 - Ethereum Basics

-> Turing Complete: it refers to a machine (or programming language) that, given enough time and memory along with the necessary instructions, can solve any computational problem, mo matter how complex. Most modern programming languares (including Solidity) are turing complete.

-> Solidity: is the official language for Ethereum. It is used to write smart contracts for Ethereum and various other blockchain networks.

-> Bitcoin:

* A limited system that is only used to decentralize finance;
* The original cryptocurrency. Thought as a form of digital gold;
* Turing incomplete;
* Only capable of understanding a limited instructions set.

-> Introduction To Turing Completeness:

* All modern programming languages are Turing complete (Python, C++, JavaScript);
* To be Turing complete a language needs to be able to do anything a Turing machine can do;
* A TUring machine is an endlessly long piece of tape that has a read/write head. It can read/write 0's and 1's in the cell on the tape. This allows anything to be computed;
* Alan Turing invented computer science and the idea of the computer.

-> Turing Machine Requirements:

* Must be able to perform conditional branching:
    * Jump/Go To Block;
    * If, Then, Else.
* Can express any possible program:
    * Loops and/or recursion;
    * Repeat until (while loops);
    * May contain infinite loops.
* You cannot predict or prove the final state of a Turing complete language;
* Bitcoin is Turing incomplete. This means the final state of any program can be proven before running it.

-> Introduction to Ethereum:

* Turing complete;
* Does not only provide decentralized finance. It is considered a decentralized development platform;
* Allows development and usage of decentralized apps with the use of the native Ether token;
* Has a programming language called Solidity that allows you to write code (smart contracts) that are hosted on the blockchain;
* Smart contracts allow for programs/applications that implement voting, games, exchanges, auctions and much more to be decentralized;
* Ethereum's goal is to decentralize the internet. Not just finance.

-> Differences of Ethereum and Bitcoin:

Ethereum is different that Bitcoin as it provides a development platform that anybody can use to write decentralized applications, Bitcoin is simply used for decentralized finance while Ethereum aims to decentralize all aspects of the internet. With Ethereum users can create self-executing smart contracts that run in a turing complete environment.

While Ethereum may sometimes be faster than Bitcoin it's speed is not guaranteed and speed is not a major differentiator between the cryptocurrencies.


# 3 - Smart Contracts and DApps

-> DApp: stands for "Decentralized Application" and is an application that runs on a blockchain and utilizes the blockchain as it's single source of truth.

-> Smart Contract: is a simply code that is stored on the blockchain that runs when certain conditions are met. Smart contracts are utilized to implement purchase/sale agreements, currency exchanges, ERC-20 and ERC-721 tokens and various other decentralized applications.

-> Smart Contracts:

* Programs that are stored on the blockchain and run when predetermined conditions are met;
* Used to automate the execution of an agreement so that all participants are immediately certain of the outcome;
* Smart contracts have the following properties:
    * Immutable;
    * Transparent/Public;
    * Executed by nodes on the network;
    * Cost money (crypto) to deploy;
    * Can hold a balance, just like a regular address.

 -> Smart Contracts Continued:

* Only run when called upon and provided gas;
* All operations are traceable and irreversible;
* Anyone can deploy a smart contract but inde they are deployed they cannot be changed or deleted;
* Cannot make HTTP requests or rely on any data outside of the blockchain;
* DApps or Decentralized Apps are made up of one or multiple smart contracts.

-> DApp Examples:

* Auctions;
* Games;
* Sale of Assets;
* Decentralized Exchanges;
* Web Browsers;
* Credit Services.

-> Example of a Smart Contract:

Lets make up the situation that i want to sell a house, so i create a smart contract of 100 ETH for the house. The smart contract will be saved in a block inside of the Ethereum network. To be deploy it is needed to pay a deploy fee. Lets say someone want to buy the house it will send a transaction of 100 ETH and the deed of the house would go to the person that bought.


# 4 - ERC-20 Tokens

-> Token: relies on a blockchain network and is created by a smart contract;

-> Coin: is the native cryptocurrency of a blockchain network. FOr example, Ether is the native coin on Ethereum;

A voin is the default cryptocurrency for a blockchain, Ethereum and Bitcoin are both examples of coins. Tokens are created on a blockchain like Ethereum by using smart contracts, anyone can create a token by writing a smart contract that adheres to the ERC-20 token standard.

-> ERC-20 Token: represents a standard for fungible tokens on Ethereum. Contracts that represent an ERC-20 token must implement specified functionality that allow for uniform usage/behavior of these tokens;

-> Fungible: refers to the ability to replace or to be replaced by another identical item. ERC-20 tokens are fungible tokens.

-> ERC-20 Tokens:

* Fungible token on the Ethereum network follow a standardized protocol know as ERC-20.
* Fungible: able to replace or be replaced by another identical item; they are mutually interchangeable;
* Non-Fungible: unique tokens; represent a unique assets such as a piece of art (for example NFTs);
* ERC-20 Tokens can be created by anyone by deploying a smart contract that adheres to the protocol;
* The ERC-20 protocol aims to standardize token functionality;
* ERC-20 Smart contract define total token supply, how tokens are created/deleted, if/how tokens can be transferred and much more.

-> ERC-20 Token Use Cases:

* Crowdfunding;
* Voting Rights and DAOs;
* Representation of Ownership;
* Paying for features/DApps:
* Enterprise Software;
* Stable Coins;
* Royalties.


# 5 - ERC-721 Tokens

-> Non-Fungible: refers to something that is unique and cannot be replaced. Non-Fungible tokens (NFTs) are unique tokens that cannot be interchanged and all have their own unique id.

-> ERC-721 Token: represents a standard for non-fungible tokens (NFTs) on Ethereum. Contracts that represent an ERC-721 token must implement specified functionality that allow for uniform usage/behavior of these tokens.

* ERC-71 tokens can be created by anyone by deploying a smart contract that adheres to the protocol;
* Each ERC-721 token has a unique id;
* Each token may be associated with metadata such as images, vídeos, sound, attributes etc;
* ERC-721 tokens are useful for proving ownership of unique items.


# 6 - Blockchain Comparisons

-> Layer 1: refers to the base blockchain network such as Ethereum or Bitcoin and its underlying infrastructure Layer 1 networks can validade transactions independetly.

-> Layer 2: refers to a protocol that relies on an integration with an existing Layer 1 blockchain network. Layer 2 networks are typically faster or provide scalability solutions but may lack decentralization and security.

-> Layer 1 & Layer 2 Chain:

* Layer 1: refers to a base network, such as Bitcoin, BNB Chain, or Ethereum and its underlying infrastructure:
    * It is very difficult to improve the scalability;
    * Can validate and finalize transactions without the need for another network.
* Layer 2: refers to a secondary framework or protocol that is built on top of an existing blockchain:
    * Performs computations or transactions off-chain and reports it back to the main chain for validation;
    * Feature solutions such as roll-ups, state channels, sidechains and more;
    * Can provide must higher thoughput, faster transaction processing time and often lower fees;
    * Often lack decentralization due to limited adoption and usage.


# 7 - Stablecoins

-> Fiat-Collateralized: are coins that hold fiat currency (such as USD, CAD, EUR) as a reserve assets. They are typically audited regularly and must hold at least 1$ fo reach coin minted.

-> Crypto Collateralized: is a coint that holds other cryptocurrencies as reserve assets. Due to the volatillity of cryptocurrencies they typically hold excess amounts in reserve.

-> Algorithmic Stablecoin: mantains it's price stability by manipulationg the supply of coins to adjust it's price. It does this using a smart contract/code.

-> Endogenous: refers to originating inside the system. In the context of stablecoins, endogenous reserve assets exist inside of the protocol.

-> Exogenous: refers to originating outside the system. In the context of stabelcoins, exogenous reserve assets exist outside of the protocol.

-> Stablecoins:

* A cryptocurrency asset whose buying power stays relatively the same;
* A non-volatile cryptocurrenc asset;
* Useful as a medium of exchange due to the volatility of most cryptocurrencies;
* Can be thought of as digital "cash";
* May be pegged to a currency like the U.S. Dollar, tangible assets such as gold or the value of another cryptocurrency;
* Pursue price stability by maintaining reserve assets as collateral or through algorithmic formuas that are supposed to control supply.

* Stablecoin Properties:
    * Relative Stability;
    * Stability Method;
    * Reserve Assets.

-> Relative Stability:

* Pegged:
    * Value pegged to another asset;
    * For every coin minted a dollar of reserve asset is hel;
* Floating Value:
    * Used math and various mechanisms to keep the byuing power the same over time;
    * Value changes (floats) to keep the buying power the same.

-> Stability Method:

* Governed:
    * Requires human intervention to control the price;
    * Considered centralized;
    * Regulated and regularly audited;
    * Requires a central entity to inject collateral in the system;
* Algorithmic:
    * Code/smart contracts facilitates burning and minting of coins;
    * Requires no human intervention.

-> Reserve Assets:

* Exogenous:
    * Collateral exists outside of the protocol;
    * Tether uses the US dollar as collateral, which exists outside of the protocol, hence it uses exogenous collateral;
    * Dau uses multiple cryptocurrencies and other stable coins as collateral; hence it uses exogenous collateral.
* Endogenous:
    * Collateral exists inside the protocol;
    * Terra used LUNA as collateral, which existed inside the protocol, hence it used endogenous collateral;
    * Using endogenous collateral is dangerous when people lose faith in the collateral and the stable coint at the same time.


# 8 - Introduction to Oracles

-> Oracle is an entity that provides off-chain data to the blockchain for use in smart contracts. Chainlink provides one of the most popular decentralized oracle networks,

* A trusted 3rd party that gives reliable information;
* Allow our smart contracts to utilize third party data;
* Code that is written by trusted third parties;
* Off-chain oracles send data to the blockchain through a transaction so it can be used by smart contracts and validated.

-> Chainlink:

* Layer 2 solution that relies on Ethereum;
* It provides a bridge between blockchain networks and data sources;
* Referred to as blockchain middleware;
* Node operators lock up currency (collateral) and provide data to the chainlink network:
    * Multiple operators provide the same data to ensure data is valid;
    * If nodes submit incorrect data they may lose collateral;
    * Chainlink determines if nodes are reliable and sends data requests to certain trusted node.
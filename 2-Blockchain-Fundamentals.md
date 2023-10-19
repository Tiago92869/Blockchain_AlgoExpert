# 1 - Introduction to Blockchain and Web3

Differences between Web 1.0, Web 2.0, Web 3.0

->Web 1.0 (1991 to 2004):

* Mostly Static pages;
* Referred to as the read-only web;
* Running advertisements was banned;
* Mostly used for information and research;
* Frames and tables were used to position and align elements.


-> Web 2.0 (2005 to current era):

* Web 2.0 refers to worldwide websites which highlight user-generated content;
* Interactions, social media, communities, GUI's;
* Lage focus on UI/UX design; 
* Brought the popularity of AJAX and JavaScript for dynamic websites;
* Community focused;
* User adta owned and controlled by intermediaries (Google, Facebook, Amazon).


-> Web 3.0 (the future of internet)

* Large focus on backend systems, databases and ledgers;
* Data ins't owned by a single party. It is shared;
* Portable and personal;
* Immersion over interaction;
* Blockchain and decentralization;
* Artificial inteligence.

Difference between Web2 and Web3 is that the data is owned by the site 
in web3 there is no owner to the data, data is shared between the people.

-> Introduction To Blockchain

A blockchain is a system of recording information in a way that makes it difficult or impossible to change, hack, or cheat.
A blockchain is essentially a digital ledger of transactions that is the duplicated and distributed acress the enire netweork of computer systems on the blockchain.
A blockchain is not owned by a central entity.

# 2 - Centralized vs Decentralized

->Centralized Systems:

* Most systems we use today are centralized (goolge, amazon...);
* Systens controlled by a single entity.


->Decentralization Systems:

Is the process by which the activities of an organization particularly those regarding planning and decision making, are distributed  or delegated away from a central, authoritative location or group.

Decentralized systems allow for trust-less interactions


->Advantages and Disadvantages:

|  Centralized  Systems  |  Decentralized Systems  |
|:-----------------------|------------------------:|
|  Low network diameter, allowing fast flow of data  |  Large network diameter (participants may be many edges away from each other), meaning data may flow slower  |
|  Simple to implement and usually highly performant  |  Difficult to implement with lower throughput, causing lower performance  |
|  Data conflicts are easily solved and synchronization is easy and clear  |  A complex protocol is needed to dispute data conflicts and find a resolution. Synchronization is difficult  |
|  Single point of failure. Easy to take down or offline  |  No single point of failure. Network can still function if a large portion of participants are taken down or offline  |
|  A central authority can sensor/change or delete data  |  Censorship is much harder and its almost impossible to change or delete existing data  |
|  Participation is regulated by central authority  |  Anyone can participate in the network; there are no "gatekeepers"  |


# 3 - Ledgers

A ledger is simply a collection or store of financial accounts or information. A blockchain is said to be decentralized, distributed ledger of verifiable transactions.

For example, we have a ledger between Bob and ALice, the ledger records all the financial transactions between the two, but anyone of them can just edit the ledger if they wanted and add fake transactions. To fix that we can add a intermediate between they and the ledger. For example a bank, Bob and Alice trade with the money they have in the bank, and the bank keeps track on the transactions writing in the ledger. But at  the same time, the someone in the bank can create false transactions in the ledger, so the ledger  ins't 100% secured. To fix this problem we introduced blockchain.

Just to verify, a blockchain is a distributed, decentralized, publicly available ledger of transactions that are verified.

THere are some properties that allowed us to trust  in blockhain:

* Immutable: unchanging over  time or unable to get changed;
* Publicly Available: available to anyone in the general public;
* Decentralized: controlled by several local offices or authorities rather than one single one;
* Distributed: shared or spread out;
* Chronological: starting with the earliest and following the order in which they occured;
* Irrevocable: not able to be changed, reversed, or recovered.


# 4 - Wallets

The next  information is more in correlation with bitcoin but other blockhains netweorks can be identicall.

The components of a wallet:
* private key (the most important)
* public key
* address

-> Private Key: the private key of an account acts as the password for that account. Any person with access to the private key can send/sign transactions and access the funds  associated with that private keys account. Private keys should be stored  in a secured location and should never be shared online or with other people.

-> Public Key: is generated from the private key and a hash function and acts as the identifier for an account. Nodes on a network can validate transactions that were signed properly using an account's public key. It is safe to share your public key (a public key is a longer and less convenient form of an address). 

-> Address: On ethereum, an address is made of 20 bytes and is a more convenient and shorter version of an account's public key.

-> Hash Function: are know as "One-way" functions that have no known inverse. They are the foundation of modern internet security and cryptography. Hash functions have the following properties:

* Fast to compute;
* Generate a uniform output;
* No known inverse;
* Deterministic;
* Very rare hash collisions.

In a more simple way:

Private Key -> Hash Function -> Public Key -> Hash Function -> Address

-> More about the Hash Function:

In normal functions for example y = f(x) you can determine the inverse for example f(y) = x, but in hash functions you can't determmine inverse ofthe function. In other words you can't determine the input from the output.


# 5 - Transactions

A transaction are tech mechanism that allows us to send value across cyberspace.

A transaction has this format:

* FROM
* TO
* AMOUNT
* SIGNATURE
* GAS/FEE
* Transaction Hash

In ethereum there are two more fields, nonce and data.

-> Flow of the Transactions:

* First we create the transaction with the data above;
* Next we transmit this to a transaction-pool;
* Transaction Pool is where the transactions go before going to the blockchain;
* Miners will validate the transactions inside of the Transaction Pool;
* After validating the miners will start to assembly a block;
* The block will contain more than one transaction;
* After the block checks for all requirements it will be sent to the blockchain.

-> Creating a transaction

Inputs: 
The inputs are transactions to prove that you have at least the amount + fee in your wallet, that's why there is change, because you can give more than you need.

Outputs:
* to address;
* amount;
* fee;
* change.


-> Digital Signature:

Is the prove that we can send a transaction.
In the context of blockchain networks, a digital signature is attached to a message or transaction to prove that the sending user has adequate permissions. TO create a digital signature you require the private key (signing key) associated with the public key of the sender of the transaction.

From all the message date of the input e pass that from a hash function and create a transactional hash (enconde the message). After that we can now generate a digital signature. There are two types:

* Signing Key -> private key;
* Verification Key -> public key.

The signing key is used to sign the transaction hash and the verification key is to decrypt the signature and determine the transactional hash associated with. 

This is the process of the keys:

message -> hash func(x) -> transactional hash || generate a hash from the message of the transaction.

SK, transaction hash -> Signature func(x) -> Signature || generate a digital signature from the signing key and the transaction hash after passing by a encrypt function.

VK, Signature -> Verification func(x) -> transactional hash || the miners select the signature from the transation and the verification key and pass by a decprition function to generate a transactional hash. 

And if the transactional hash is the same from the transactional hash generated from message it means that the signature is valid.


# 6 - Blocks

-> Block:

In typical blockchain networks a block is a place where blockain data (like transactions, or any type of logs) is stored. In the Bitcoin blockchain contains the following properties:

* Magic Number, just a simple number for a specific blockchain;
* Block Header;
* Block Size, size limit of the block, maximum amount of data that can be stored;
* Transaction Count, number of transactions in the block;
* Transaction Data, all the transaction data; 
* Version;
* Previous Block Hash, reference of the previous block, is important to link blocks;
* Hash Merkle Root, quick way if a transaction is part of a specific block and if its valide;
* Timestamp;
* Bits/Difficulty, the more dificulty the hardest it is to actually mine it;
* Nonce, its added by the miner as proof that the block is valid;
* BLock Reward, how much bitcoin is given to the miners after mining a block.

-> Genesis Block:

On te Bitcoin blockchain, the Genesis Block is the first block ever created. It contains special information about the blockhain network as a whole.

It as the same data as any other block and it has some more special data:

* Difficulty and Difficulty Interval;
* Mining Reward and Reward Changes;
* Circulation Supply, defines the number of tokens allowed in circulation;

-> Nonce:

A nonce is a special number that is added to the contents of a block by miners. The nonce is used to make the hashs of a block start with a certain number of zeros, it provides the proof of work for a block.

# RangeCoin
Focusing on the long-chain market of the blockchain ──constructing a multidimensional Token economic ecological community

rangecoin coinrange@gmail.com

Note: must support Range because this change your life any the crypto world!

note
This white paper and any other documents related to this white paper relate to the intended development and use of the RangeCoin network. They are for reference only and are subject to change.

This white paper describes a project under development
This white paper contains forward-looking statements based on RangeCoin's beliefs and certain assumptions and information provided by RangeCoin.

The RangeCoin network envisaged in this white paper is under development and is constantly being updated, including but not limited to key governance and technical features. RangeCoin involve and involve the development and use of experimental platforms (software) and technologies that may not achieve or achieve the goals set out in this white paper.

If the RangeCoin network is completed, it may be very different from the network specified in this white paper. We make no representations or warranties with regard to the achievements or reasonableness of any plans, future forecasts or prospects, and nothing in this document is or should not be taken as a promise or statement of the future.

No regulated products available
RangeCoin is not intended to represent securities or any other regulated product in any jurisdiction.

This document does not constitute an offer or solicitation for securities or any other regulated product, nor does it constitute a promotion, invitation or solicitation for investment purposes. The terms of purchase are not a document or any form of prospectus intended to provide financial services.

RangeCoin do not represent the rights of equity, shares, units, royalties or capital, profits, returns or income of the platform or software or RangeCoin or any other company or intellectual property related to the platform or any other public or private. Businesses, companies, foundations or other entities in any jurisdiction.

This white paper is not a recommendation
This white paper does not constitute a recommendation to purchase any RangeCoins. Do not rely on any contract or purchase decision.

Risk warning
Buying RangeCoin and participating in the RangeCoin network will bring great risks.

Before purchasing RangeCoin, you should carefully evaluate and consider the risks, including those listed in https://web.rangecoin.xyz/ and any other documents.

RangeCoin perspective only
The views and opinions expressed in this white paper are the views and opinions of RangeCoin and do not necessarily reflect the official policies or positions of any government, quasi-government, authority or public agency, including but not limited to any regulatory agency in any jurisdiction. Any jurisdiction.

The information contained in this white paper is based on sources believed to be reliable by RangeCoin, but its accuracy or completeness cannot be guaranteed.

Chinese is the authorized language for this white paper
This white paper and related materials are issued in English only. Any translations are for reference only and have not been certified by RangeCoin or anyone else. The accuracy and completeness of any translation is not guaranteed. If there is any inconsistency between the translated version and the Chinese version of this white paper, the Chinese version shall prevail.

No third party recognized affiliation
References to specific companies and platforms in this white paper are for illustrative purposes only. The use of any company and / or platform name and trademark does not imply any association or endorsement with any party.

You must get all the necessary professional advice
Before deciding whether to buy RangeCoin or otherwise participate in the RangeCoin network, you must consult with a lawyer, accountant and / or tax professional, and any other professional adviser.

RANGE overview
The RANGE network is named because we want to make new range in the crypto world

The total number of RANGE coins is around 23 million;

All currencies are generated directly in the genesis block, and the account number that generated the genesis block is RANGE-QXCN-7NR9-Q5RT-5M7TL. The balance of this account is also set to negative 23 million. The negative monetary value in the genesis account also has several interesting effects:

The Genesis account cannot initiate any transactions and cannot pay transaction fees, because the account balance is negative, so the password of this account is also public (note that the last one is also part of the password): It was a bright cold day in April, and the clocks were striking thirteen.

Any RANGE currency sent to this account will be destroyed, because the negative balance of this account will make the transferred currency and the balance offset each other;

The RANGE assets transferred to this account will also be destroyed;

The relationship between RANGE and NXT
The RANGE network is based on the NXT blockchain and currently uses the NXT 1.11.13 GPL version


RANGE contributes walletnxt on NXT https://walletnxt.com This is the only NXT decentralized wallet that supports all NXT clone projects. The current number of users is 1100+

100% POS (Proof Of Stake) Proof of Stake
In RANGE's POS model, security is guaranteed by the holders. The benefits brought by POS will not generate a centralized trend in POW

/////////////////

The system built by RANGE regards each coin as a tiny mining machine. The greater the number of coin coins in the account, the greater the chance that it has the opportunity to generate a block. The benefit of creating a block is the transaction costs within the block. Creating a block does not generate new coins. The redistribution of HEBE takes place in the transaction fees for creating blocks.

Transparent forging replaces mining.

Subsequent blocks generate verifiable, independent, unpredictable information based on the previous block. Create a series of blocks that can be traced back to the genesis block. The block generation time is set to 60s. But the diversity of possible results has led to an average block generation time of 80s, and occasionally very long intervals.

Security has always been a concern for POS systems. Here are the basic concepts of POS algorithms:

The accumulated difficulty value is stored as a parameter in each block, and the difficulty value of the next block will be derived from the previous block; in order to prevent inconsistencies, the network will select the maximum accumulated difficulty value of the entire block chain.

In order to prevent a person from transferring equity between different accounts to increase the chance of acquiring block creation opportunities, newly transferred tokens must stay at least 1440 blocks before being allowed to participate in the block generation system. The currency that meets this standard can be the effective equity of the account. This value will determine the probability of obtaining forging;

To prevent attackers from always generating new block chains from the genesis module, the network only allows chain reorganization to start from the first 720 blocks at the current height. Any submitted block height below this value will be rejected;

Due to the low probability of controlling the blockchain by a single account, once a transaction is confirmed by a block and at least 10 blocks are generated, at this time the transaction is considered securely confirmed

Network node
image

A network node refers to any device that contributes transactions and block data on the network; any device running the RANGE service can be regarded as a node;

Network nodes can be divided into two types, hallmarked and ordinary nodes; hallmarked nodes are nodes with an encrypted signature, which is generated using the account's private key. This signature can be decoded to analyze the id and balance of the account bound to this node; nodes with a hallmark signature can be considered as account bound, so this node will be more secure; the balance bound to the node The more credibility is, the higher the credibility may be; an attacker may want to gain trust to conduct an attack through the Hallmark node bound to the account, but the cost of obtaining trust prevents this behavior from happening;

Any node in the RANGE network has the ability to process and broadcast transactions and block data. The block information received from other nodes will be checked for validity; in order to prevent the propagation of invalid data, nodes that generate invalid data will be temporarily blackened for a period of time;

In order to prevent DDOS attacks, each node's request to receive other nodes is limited to 30 per second;

Block
Like other electronic currencies, all transaction account information of RANGE is stored in a series of blocks, called the blockchain. This ledger provides a permanent record of transactions and the order in which the transactions took place; in the RANGE network, the blockchain exists in each node, and the unlocked account (submitting the private key) on any node is the first transaction recorded in the account. After the occurrence of the 1440th block, it has the ability to generate blocks. Accounts that meet these conditions also become active accounts.

image

All blocks contain the following information:

Block version, block height value, block ID

Block creation time, the unit is second, the number of seconds from the creation block to the present;

Create the account ID of the block and the public key of the account;

ID and hash value of the previous block, the number of transactions contained in this block

The total number of RangeCoins and fees generated from the transaction;

Data for all transactions in the block, including transaction ID

Block effective data length and hash value of valid data

Block generation signature

Signature of the entire block

Base target value and cumulative difficulty value

Block generation
Three key parameters determine which account is eligible for block generation, which account has the right to generate a block, and which block is selected as the final block to avoid conflicts: basic target value, target value and cumulative difficulty value;

Base target
In order to win the right to forge (generate blocks), the RANGE account does this by generating a hash value that is smaller than the given base target value. This basic target value is very different with the generation of the block. It is derived from the basic target value of the previous block multiplied by the time (in seconds) from the generation of the block to the previous block.

Target value
Each account will calculate this value based on the effective equity of the account

Cumulative difficulty value
The cumulative difficulty value is also derived from the base target value

Forging Algorithm
Each block on the blockchain contains a generated signature field. To participate in the block generation process, the active account must use its own public key to recalculate the previous block to generate a signature. The generated 64-byte signature is then calculated again using the SHA256 algorithm, and the first 8 bytes of data of the resulting hash value are used as the hit value for this account.

This hit value will be compared with the current target value. If hit <target value, the next block can be generated. According to the above formula for calculating the target value, the target value will increase with time. Even if there are very few active accounts on the network, the target value will become very large over time, so eventually there will be an account for block generation. This inevitable result has led you to estimate how long it will take to generate a block by calculating the target and hit values ​​of any account.

The last point is very meaningful. Because any node can query the balance information of any active account, it is possible to calculate the hit value of all accounts in a loop. This means that there can be informed predictions about which account will become the forge of the next block. This led to a possible disorder attack, which was achieved by transferring the balance to the next generator, which is why it takes 1440 confirmations before the balance can become a valid balance. It is interesting that the underlying target value of the next block cannot be educated, so the randomness of the block generator after prediction will become abnormally large.

Once an account has won the right to generate blocks, it can bind up to 512 transactions to the block, filling all the necessary information to produce blocks. This block is then broadcast to the p2p network as a candidate block;

The node receiving the block in the network will verify the payload value of this block, generate an account, and all the signature information of the block. In the case where multiple blocks are generated, the node will select the block with the highest cumulative difficulty value as the final block. Because the block data is shared between the nodes, by checking the difficulty value of the block, the invalid branch will be Will be removed.

Balance lease
As the effective balance of the account affects the forging ability of the account, it is feasible to lease the forging ability of the account to other accounts, but without losing control of the RangeCoin. Initiating an account control type transaction, the account lessor will temporarily lose the effective forging amount, and the account receiving the rental capacity will increase the corresponding forging capacity value; the receiver will lose these additional forging balances when the lease expires , These balances will be returned to the previous lessor.

An account with a rental balance makes it easier to forge blocks and earn more fees. But these costs are not evenly distributed to each lessor. The system allows the existence of forged pools that are not trusted by the system, and these forged pools can pay back to the participants.

account number
Brain wallet: All accounts are stored on the network, and the account address and private key of each account are calculated from the account password through a combination of SHA256 and Curve25519;

Each account can be represented by a 64-bit number. This number can detect up to 4 errors through the account address generated by Reed-Solomon code RS7) and automatically correct up to two errors. This feature can organize the loss of HEBE currency, assets, etc. due to misspelling the address of the other party to the transaction. The account address will be prefixed with HEBE- so that it can be easily distinguished from other currency addresses.

The process of generating a Reed-Solomon-encoded account address determined by the private key is as follows:

The HASH value generated by the password through the SHA256 algorithm is used as the account's private key;

The private key generates the public key of the account through the Curve25519 algorithm;

The public key uses the SHA256 algorithm to generate the account ID;

The first 64 digits of the account ID are visible account numbers;

Reed Solomon coded this visible account number and added the prefix HEBE- to finally generate the account address;

When an account is first accessed through a password, its public key is still not secure. When the first transaction occurs, the 256-bit public key information will be stored in the block, which also ensures the security of the account. The address space 2256 of the public key is larger than the address space 264 of the account number, so there is no one-to-one relationship between the account number and the password, and conflicts may also occur. These conflicts are found and resolved in the following way: An account logged in with the specified password has been locked by a 256-bit public key, and no other public / private key will be allowed to log in to this account.

Account balance property
For each RANGE account, there are many different balance assets. Each category has a different purpose, and some are also verified during transaction confirmation and processing.

The effective account balance is used to calculate the forging capacity of the account. The so-called effective balance is that the account balance has stayed more than 1,440 blocks. In addition, the account lease allows the account to lease the effective balance to other accounts;

The guaranteed balance refers to the amount of property in the account after 1,440 blocks. Unlike the effective balance, the guaranteed balance cannot be allocated to other accounts;

Basic balance refers to the transaction amount that has been confirmed at least once;

The total amount of reward fees received for successfully forging the block when the forging balance is displayed;

Unconfirmed balance refers to the balance in the account minus the balance in unconfirmed transactions;

wallet.dat
Bitcoin and related currencies often use an encrypted file, which is called a wallet, which is used to store the address information used to accept Bitcoin. The address of the RANGE account can also be stored in an encrypted offline file.

Equity attack
Nothing at Stake In a zero-cost attack, the forge attempts to continue to create blocks on each branch of the block, because this behavior is almost costless to the attacker; in addition, ignoring any branch may cause Lead to the loss of block rewards, once a branch becomes a formal blockchain due to the greatest cumulative difficulty;

Now such attacks are only possible in theory and are not practical; RANGE networks do not experience long block branches, and low block returns cannot provide very strong benefit incentives. Furthermore, for a small benefit, the network is affected. Security and trust are worthless.

As part of the RANGE development roadmap, a feature called the "economic set" concept can provide protection against this type of attack. It detects the non-conformity in the network by forcing the transaction to include a hash value of the previous block and grouping nodes into the cluster. Normal behavior and punishment (temporary loss of forging ability)

History Attacks
In a historical attack, someone obtained a large amount of currency and sold it, and then tried to replace the blockchain data with a successful branch created before the transaction; if it fails, there will be no loss to the attacker because the currency has already Successfully sold; if the attack was successful, the attacker took back the currency they had sold. An extreme example of this kind of attack is that the attacker needs to obtain the private key of the account and then build a successful branch from the genesis block;

In RANGE, general historical attacks will fail, because all equity that can be used for forging needs to stay in the block to 1,440; in addition, the effective balance will be part of the block verification when the account generates each block. Extreme forms of attack will also fail, as RANGE's blockchain does not allow for more than 720 height reorganizations. This limits the attacker's ability to achieve a successful attack from a time frame;

RANGE function
Asset system:
Users can create their own exclusive projects on RangeCoin and conduct secure and fast peer-to-peer transactions on the HebeBlock asset exchange built into the system. This eliminates the need to transfer assets or place trust in an external agency or business.

Monetary system:
The RangeCoins currency system allows users to create and trade their custom currencies. At the same time, as a specific class of assets, currency will have a number of additional features, such as the ability to use HebeToken to maintain its stable value.

Data Cloud:
The HebeBlock data cloud is a decentralized data storage system that provides tamper-resistant timestamps. This allows legal records (such as contracts) to be embedded in the blockchain and gives absolute accuracy to when they were created.

Voting system:
Decentralized systems and organizations need a means to reach consensus. The HebeBlock voting system is part of the HebeBlock account control system, allowing a group of users to approve or reject transactions. The results of HebeBlock voting can be used in many ways, depending on the characteristics of the project.

Account Control:
HebeBlock accounts can secure digital assets through enhanced multi-signature methods. The account owner can set the account to be restricted by the voting system mentioned above, which means that the user can restrict access to the account by some unknown sources or prohibit transactions without the approval of multiple parties.

Anonymous mixed currency:
Anonymous coin mixing is a decentralized anonymous privacy service that allows users to quickly and efficiently mix funds with other users, creating a random mapping relationship between existing user accounts and new accounts after coin mixing, thus Achieve complete anonymity.

It aims to solve the inconvenience of users in managing multiple digital currencies. In the future, more blockchain support and HEBE functions will be gradually added to make a decentralized wallet that supports the most chains.

RANGE discount 
The shopping rebate platform is currently running normally, and the profit is used for repurchase / destroy Hebe, to list (for a certain platform, the purchase rebate profit 20w repurchase)

RANGE Centralized Exchange
Currently being tested, RANGECOIN is used as a platform currency, which can be used for fee reduction and exemption, etc. The platform profit is used to repurchase.

The interface is as follows: (for reference only, the final product may not be the following picture) image image

RANGE Decentralized Asset Exchange
An asset decentralized exchange based on the Rangecoin blockchain can support Range to purchase other assets, such as (assets Btc, Eth ...)


Initial token distribution
On Genesis, the token totall supply is 23,333,333 RANGECOINS. The distribution plan of RANGECOINS is as follows:

Private placement: 25%

RangeCoin development team: 15% (from the start of RANGE, the team will unlock 1,000,0 per month, all of which are expected to be unlocked in 12.5 years)

HEBE Foundation: 15% (reserved to support the operation of the foundation)

Ecosystem development: 40% (residential applications; subsidies to potential users; incentives to outstanding partners; potential public sales)

RANGE payments app Airdrop: 5% (used to attract users, early support for NXT and Ardor, as the wallet currency increases, the supported currencies will also increase)

Proceeds from the sale of RANGECOINS will first be used for the development of the RANGE network. The planned usage distribution is as follows:

Foundation operations: 10% (including service provider and contractor costs, such as audit, consulting, legal and other third-party costs, and other administrative costs)

Software development: 50% (including costs, expenses and expenses directly attributable to release development)

Developer support: 10% (including funding hackathons, rewarding volunteers, and training programs)

R & D sponsorship: 10% (including conferences, research programs, and university outreach)

Marketing and promotion: 20% (including business development, community planning and outreach, and related travel, communication, publishing, distribution and other expenses)

route map
The expected RANGE projects are as follows. We reiterate that the roadmap is for reference only and is subject to change.

The first phase (September 2018 ~ March 2019) will focus on the launch and operation of RANGE. We also release initialized mobile clients for the RANGE network

The second phase (February 2019 ~ April 2019) will focus on the exchange sale of RANGE, and contact the exchange

The third stage (April 2019 ~ December 2019) formed the RANGE team, developed a new web wallet, developed the HEBE mobile client, and developed a centralized exchange.

The fourth phase (after January 2020) will focus on the underlying rewrite of the HEBE network, improve the efficiency of the RANGE network, further technological innovations in the HEBE SDK and mobile clients, and developer participation


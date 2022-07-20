*"Living matter is the most powerful geological force"* - Vladimir Vernadsky

<strong>Noob powered under root!</strong>

<strong>Enthusiastic blockchain</strong>

<strong>Valueless, utilitarian, experimental. NOT investemnt asset!</strong>

https://GenesisL1.com  - website

https://L1coin.org - another website

https://DatasetNFT.org - NFTized datasets for machine learning (Proteinnet) (In Progress)

https://MolNFT.io - service to NFTize molecular structures .pdb and .cif files (MVP)

https://MolNFT.org - Collections of NFTized databased such as PDB bank and Alphafold with tools (In progress)

https://explorer.GenesisL1.org - light EVM blockchain explorer

https://ping.pub/genesisL1 - Web3 light Cosmos blockchain explorer, staking and governance dashboard

https://github.com/alpha-omega-labs/genesisd - genesisd full node and installation shell scripts

noob powered under root! 

<strong>Ethermint and Evmos fork! Currently running on Evmos v0.3</strong>

GenesisL1 blockchain project is a planned, highly experimental, Cosmos SDK and Ethereum EVM (Ethermint engine) powered Layer 1 blockchain made for Arts (NFT) and in silico research methods and bioinformatics, using blockchain as a distributed, decentralized database and storage for Open distributed Art and Scientific databases.  

GenesisL1 blockchain is powered by L1 coin. All initial supply of 21M coins was gifted valueless to users and onchain community_pool to fulfill 3 core features and utilities of L1 coin and 2 core applications of L1 coin:

I. Applications:

+ recycle L1 coin on blockchain, 1L1 = 1L1
+ utilize L1 coin on blockchain, 2L1 = 2L1 

II. Utilities:

+ protecting blockchain/network and consensus
+ voting on SIGANL, COMMUNITY_POOL SPENDING, BLOCKCHAIN PARAMS CHANGE proposal
+ powering smart contracts with gas 

L1 coin may be requested from GenesisL1 community_pool by anyone (validator, developer, artist, scientist, user, group, project, etc) with proposal to fulfill core utilities, features and applications of L1 coin. 

ITS AN EXPERIMENTAL SOFTWARE AND IDEAS, AND ITS IMPLEMENTATIONS. NO WARANTY OF ANY KIND! IT MAY NOT WORK OT MAY HAVE ERRORS AND BUGS. ITS VOLUNTARY AND OPEN SOURCE.

<div align="center"><h1>Genesis L1 blockchain</h1></div>

<div align="center"><h2>Renaissance, above money & beyond crypto</h2></div>
Genesis L1 is experimental decentralized blockchain project that is powered by top notch open source software to establish decentralized new Layer 1 blockchain for Arts and Science with absolute Ethereum compatibility and Green*!
<br>
<sub>*All Genesis L1 basic blockchain/network infrastructure uses energy from renewable sources: Energy from wind and hydropower!</sub>

<br>

<div align="center"><h2>GENESIS L1 MAINNET:</h2></div>

To connect to Genesis L1 testnet with metamask or other geth compatible software, you can use the following endpoints
+ Network Name: Genesis L1 Testnet
+ New RPC URL: https://rpc.genesisl1.org/
+ Chain ID: 29
+ Currency Symbol (optional): L1
+ Block Explorer URL (optional): https://explorer.genesisl1.org/


+ Additional RPC URL: https://rpcb.genesisl1.org/

<div align="center"><h3>Genesis L1 Mainnet node install script</h3></div>

+ <code>git clone https://github.com/alpha-omega-labs/genesisL1.git </code>
+ <code>cd genesisL1</code>
+ <code>sh mainnet-node.sh mynewnodename</code>

Set your own node name and put it to <strong>mynewnodename</strong>

<div align="center"><h3>Genesis L1 Mainnet validator install script</h3></div>
create-validator.sh in genesisL1 project folder</br> 

THIS SCRIPT WILL CREATE VALIDATOR FROM YOUR GENESISL1 NODE </br> 
Please, with on Ubuntu 18/20. 

+ <code>git clone https://github.com/alpha-omega-labs/genesisL1.git </code>
+ <code>cd genesisL1</code>
+ <code>sh create-validator.sh YOUR_VALIDATOR_NAME YOUR_PRIVATE_KEY AMOUNT_STAKED COMISSION_RATE</code>

*YOUR_PRIVATE_KEY is a private key from your Ethereum address (public key) where your L1 are stored (in genesisL1 mainnet!!!). </br>
<strong>!!!USE NEW SEPARATE KEY FOR L1!!! </strong>
</br>
amount must be specified in minimal coin units (aphoton, like wei in Ethereum): </br>

1 L1 = 1 000 000 000 000 000 000 aphoton
</br>
comission rate must be specified in range from 0.01 to 0.99, where 0.01 = 1% and 0.99 = 99%, for example if you want commission rate = 5%, it should be specified as 0.05 in script
This script will create your new genesisL1 validator.</br>
You should run this script on fully synchronized node.</br>
sh mainnet-node.sh</br>
You can check status of your node service with:</br>
service genesis status</br>
This script should be running with arguments:</br>
-YOUR_VALIDATOR_NAME</br>
-YOUR_PRIVATE_KEY (please, use NEW keys to avoid issues!!!)</br>
-AMOUNT_STAKED (in aphoton, 1aphoton = 1wei)</br>
-COMISSION_RATE(0.01 = 1%; 0.99 = 99%)</br>
Be ready to submit new password to encrypt your key and remember it. </br>
Example that will create validator named "supervalidator" with 1000L1 self stake and 10% comission:</br>
sh create-validator.sh supervalidator 58a86862565e596bcf185d699ef4db6a8f02f6696f4a3fe6ff5cf5c0b451c866 1000000000000000000000 0.1

<div align="center"><h2>GENESIS L1 TESTNET:</h2></div>

To connect to Genesis L1 testnet with metamask or other geth compatible software, you can use the following endpoints
+ Network Name: Genesis L1 Testnet
+ New RPC URL: https://testrpc.genesisl1.org/
+ Chain ID: 26
+ Currency Symbol (optional): L1
+ Block Explorer URL (optional): https://testnet.genesisl1.org/
 
<div align="center"><h3>Genesis L1 Testnet node install script</h3></div>

+ <code>git clone https://github.com/alpha-omega-labs/genesisL1.git </code>
+ <code>cd genesisL1</code>
+ <code>sh testnet-node.sh mynewnodename</code>

Set your own node name and put it to <strong>mynewnodename</strong>

<div align="center"><h3>Genesis L1 Testnet validator install script</h3></div>
THIS SCRIPT WILL SETUP YOUR VALIDATOR AUTOMATICALLY WITHOUT SECURITY IN MIND: </br> 
Will install your Genesis L1 Testnet validator node, sync it, import your Ethereum private key and create validator with specified amount of self staked L1 coins and specified validator commission.</br>


+ <code>git clone https://github.com/alpha-omega-labs/genesisL1.git </code>
+ <code>cd genesisL1</code>
+ <code>sh testnet-validator.sh mynewnodename ETHEREUM-PRIVATE-KEY amount commission</code>

*ETHEREUM-PRIVATE-KEY is a private key from your Ethereum address (public key) where your L1 are stored. </br>
<strong>!!!USE NEW SEPARATE KEY FOR L1!!! </strong>
</br>
amount must be specified in minimal coin units (aphoton, like wei in Ethereum): </br>

1 L1 = 1 000 000 000 000 000 000 aphoton
</br>
comission rate must be specified in range from 0.01 to 0.99, where 0.01 = 1% and 0.99 = 99%, for example if you want commission rate = 5%, it should be specified as 0.05 in script
Example of starting validator node with 10000L1 staked with private key from address where 100001L1 are stored with 10% validator commission rate:</br>
<code>sh testnet-validator.sh pepe 9bb98bc160504838542d40366f731dcb765e1c0c7f19847b4ccd65f35f229747 10000000000000000000000 0.1</code>

GENESIS L1 IS EXPERIMENTAL DECENTRALIZED OPEN SOURCE PROJECT, PROVIDED AS IS, WITH NO WARRANTY.

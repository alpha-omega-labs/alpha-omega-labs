*"Living matter is the most powerful geological force."* - Vladimir Vernadsky

https://GenesisL1.com <br>

https://GenesisL1.io

https://MolNFT.io

https://MolNFT.org

https://explorer.GenesisL1.com

noob powered under root! 

<strong>Ethermint and Evmos fork! Currently running on Evmos v0.3</strong>

Genesis L1 is a planned, highly experimental, Cosmos SDK and Ethereum EVM (Ethermint engine) powered Layer 1 blockchain made for Arts (NFT) and in silico biomedicine. Universal and efficient environment for creators, scientists and inventors, where you are the owner of own decentralized space, cooperating with others. All initial Genesis L1 tokens - 21 MILLION - were/is/will be gifted to a random people, mostly from average blockchain users community and NFT/dapps creators community, in a different forms, including solidity smart contracts DAO token gifts @ Ethereum blockchain and @ xdai blockchain. L1 tokens have no value of any kind by default and are strictly utility tokens with many concrete utilities essential for Genesis L1. 
Now L1 exist at three different blockchains: Ethereum, xdai, BSC. All connected via Omni Bridge.

Some of planned and current utilities of L1
+ DAO Vote
+ Genesis L1 own transition
+ DAO Proposal
+ Block validator
+ Genesis L1 blockchain vote
+ Genesis L1 vote delegation
+ Fueling distributed bio dbs
+ Queries to biomedical dbs
+ Efficient NFT creation
+ Scalable NFT distribution
+ Sharing GPU meets AI
+ Distributed datasets for ML

To receive Genesis L1 gift you have 3 different ways:
+ Just ask DAO for L1 via proposal, or just ask for DAO membership, or both. DAO has ~2.5M L1 in Commons Budget.
+ If you are a developer of blockchain, decentralized protocols, dapps - you are called creator and there are creators gifts ~ 2.5M L1 in total 
+ If you are doing anything bio/medicine related you may participate in SCI quest, where L1 gift is at the end of quest. Some are already doing own SCI quest and so already can take gifts. 1M L1 in total.

All important links are on the website.

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

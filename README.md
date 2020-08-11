# PupperCoin Crowdsale Manual
*Kovan (42) Network used for testing*

1. Compile *PupperCoin.sol* and *Crowdsale.sol* via Remix and MetaMask.

2. In *Crowdsale.sol* 'Contract' field, deploy **PupperCoinSaleDeployer** with the following parameters:
  * NAME:  puppercoin
  * SYMBOL: PPC
  * WALLET:  0x73024f7Da4d0832757f74cc96c1505Cd0dc8F79A  
  * GOAL: 300
      * Wallet used is the account previously funded on Kovan which also acts as the "from" account is these transactions
      * Contract address is **0x50ef98d467C5b4716A2218C62729c66fD368fAd6**
      * Goal amount is the maximum amount of tokens as directed in original instructions
  
3. Change the contract to Pupp

, Toggle to PupperCoin contract confirmation on kovan.etherscan.io and save contract address for later use
  * In my test-run, the contract address was **0xf684573660273341f00fd355abe0d54c66990495**
  
4. Compile  in Remix

5. Paste PupperCoin contract address (see step 3) into At Address Field and add it

6. Select **PupperCoinSaleDeployer** contract and enter the following fields:
  * NAME:  puppercoin
  * SYMBOL: PPC
  * WALLET:  0x73024f7Da4d0832757f74cc96c1505Cd0dc8F79A  
  * GOAL: 300
      * Wallet used is the account previously funded on Kovan which also acts as the "from" account is these transactions
      * Contract address is **0x52c6bff435ccc07e39548b19101c47490512ef85**
      * Goal amount is the maximum amount of tokens as directed in original instructions
 7. Toggle to **PupperCoinSale** Contract and enter a recipient address in *buyTokens* field and click
 * Note that using an external network like Kovan made the gas required to high to execute with this token amount
 * Recommend using a custom network for deploying a significant token amount in ETH

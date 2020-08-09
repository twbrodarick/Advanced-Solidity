# PupperCoin Crowdsale Manual
*Kovan (42) Network used for testing*

1. Compile and deploy PupperCoin.sol via Remix and MetaMask with the following parameters:
* Use Name:  puppercoin
* Symbol:  PPC
* Initial Supply:  0
  
3. Confirm PupperCoin contract confirmation on kovan.etherscan.io and Ssve contract address for use later
  * In my testrun, the contract address was **0x6dc840755c42e362eebf361062e74c0b2d826643**
  
4. Compile *Crowdsale.sol* in Remix

5. Paste PupperCoin contract address (see step 3) into At Address Field and add it

6. Select #### PupperCoinSaleDeployer contract and enter the following fields:
  NAME:  puppercoin
  SYMBOL: PPC
  WALLET:  
  GOAL: 300
  * Wallet is used is a Kovan-funded account I previously generated:  **0x73024f7da4d0832757f74cc96c1505cd0dc8f79a** 
   * Goal amount is the maximum amount of tokens as directed in original instructions
  * Contract address is **0x7142f8989739b1978dc714517bec26fe9da7337d**
 
 7. Toggle to PupperCoinSale Contract and enter a recipient address in *buyTokens* field and click
 * Note that using an external network like Kovan made the gas required to hiigh to execute with this token amount
 * Recommend using a custom network for deploying a significant token amount

# PupperCoin Crowdsale Manual
*Kovan (42) Network used for testing*

1. Compile *PupperCoin.sol* and *Crowdsale.sol* via Remix and MetaMask

2. In *Crowdsale.sol* 'Contract' field, deploy **PupperCoinSaleDeployer** with the following parameters:
  * NAME:  puppercoin
  * SYMBOL: PPC
  * WALLET:  0x73024f7Da4d0832757f74cc96c1505Cd0dc8F79A  
  * GOAL: 300
      * Wallet used is the account previously funded on Kovan which also acts as the "from" account for these contracts
      * Contract address is **0x50ef98d467C5b4716A2218C62729c66fD368fAd6**
      * Goal amount is the maximum amount of tokens as directed in original instructions
  
3. Change the contract to **PupperCoinSale**

4. In the 'At Address Field', paste in the **token_sale_address** and click to deploy

5. Change the contract to **PupperCoin**

6. In the 'At Address Field', paste in the **token_address** and click to deploy

7. Toward the top of the screen in the 'Value' field, input a reasonable amount of wei or ether that our wallet can fund in tokens along with the requisite gas
 * Note that using an external network like Kovan can make the gas demanded too high to execute for sizable token purchases
 * Recommend using a custom network for deploying a significant token amount in ETH

8. Toggle back to **PupperCoinSale** contract and expand selections

9. in the **buyTokens** field, enter any recipient address established on your testnet and click to purchase tokens

10. If successful, load the tx_hash in Etherscan to confirm the successful token purchase by the designated recipient
 

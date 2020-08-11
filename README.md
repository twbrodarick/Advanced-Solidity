# PupperCoin Crowdsale Manual
*Kovan (42) Network used for testing*

1. Compile *PupperCoin.sol* and *Crowdsale.sol* via Remix and MetaMask

2. In *Crowdsale.sol* 'Contract' field, deploy **PupperCoinSaleDeployer** with the following parameters:
  * NAME:  puppercoin
  * SYMBOL: PPC
  * WALLET:  0x73024f7Da4d0832757f74cc96c1505Cd0dc8F79A  
  * GOAL: 300
      * Wallet used is the account previously funded on Kovan which also acts as the "from" account is these transactions
      * Contract address is **0x50ef98d467C5b4716A2218C62729c66fD368fAd6**
      * Goal amount is the maximum amount of tokens as directed in original instructions
  
3. Change the contract to **PupperCoinSale**

4. In the 'At Address Field' paste in the **token_sale_address** and click to deploy

5. Change the contract to **PupperCoin**

6. 4. In the 'At Address Field' paste in the **token_address** and click to deploy

7. Toggle back to **PupperCoinSale** and expand selections

8. Toward the top of the screen in the 'Value' field, input a reasonable amount of wei or ether that our wallet can fund the required gas.
 * Note that using an external network like Kovan made the gas required to high to execute with this token amount
 * Recommend using a custom network for deploying a significant token amount in ETH

9. Under the **PupperCoinSale** Contract, enter any recipient address established on your testnet in the **buyTokens** field and click.

10. If successful, load the tx hash in Etherscan to confirm the successful purchase of tokens by the designated recipient.
 

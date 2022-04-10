# Blockchain_Wallets
Ethereum Transaction

**OVERVIEW**

The Search Application allows a customer to find a fintech professional and pay them for their work. 
- **FinTech_Search** file is compatible with the Streamlit library and contains the code associated with the web interface. 
The Application allows you to:
  - Generate a new Ethereum account instance by using your mnemonic seed phrase
  - Fetch and display the account balance associated with your Ethereum account address.
  - Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech candidate for their work.
  - Digitally sign a transaction that pays a Fintech candidate and send transaction to the Kovan testnet.
  - Review the transaction hash code associated with the validated blockchain transaction. 
  - Once the transaction’s hash code is recieved, you will navigate to [Kovan’s Etherscan](https://kovan.etherscan.io/) website to review the blockchain transaction details.


- **FTcryto_wallet** File contains the Ethereum transaction functions. The import statement integrate the **FTcryto_wallet** into the **FinTech_Search** interface program.Integrating these two files will allow for automating the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via a personal Ethereum blockchain called Ganache.
![etherscan-balance-receiver](https://user-images.githubusercontent.com/103196346/162598518-f29e5824-ef48-4b27-a2e2-beb8d3560fa7.png)
![etherscan-balance-sender](https://user-images.githubusercontent.com/103196346/162598520-e55be1a1-20ad-4850-86e1-2056693e381c.png)
![etherscan-transaction-details](https://user-images.githubusercontent.com/103196346/162598527-74078fbf-7bcb-4b93-8a1e-51c5a0733664.png)

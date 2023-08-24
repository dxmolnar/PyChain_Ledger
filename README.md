# PyChain Ledger

This project involves developing a Streamlit application named "PyChain Ledger." This application is designed to chronicle transaction data within a blockchain. Unlike traditional ledgers, blocks cannot be deleted—only new data can be added. Furthermore, the application can verify the blockchain's integrity and display its transactions in a structured dataframe format.

The original code was modified as follows: 
1. A new data class "Record" was created
2. Modified the Block Data Class to store Record Data
3. Implementing the caching decorator in Streamlit
4. Ran PyChain Ledger: See results below

How to set up the app?
1. Clone this repository: https://github.com/dxmolnar/PyChain_Ledger.git
2. Install the necessary repos: Pandas and Streammlit "pip install pandas streamlit"
3. Run the app as "streamlit run pychain.app"
4. Test the app in the browser


How to run the app?
1. Fill out the necessary fields.
2. Add the txn to the Block
3. Validate the Chain
   
<img width="1087" alt="PyChain_Ledger_Inst" src="https://github.com/dxmolnar/PyChain_Ledger/assets/127795314/9eca1844-12e4-4574-81d7-30fa8e8b54a1">

Validation
1. Check the Block Inspector in the sidebar
2. Check the PyChain Ledger for the txns.
   
<img width="1087" alt="PyChain_Ledger_Inst2" src="https://github.com/dxmolnar/PyChain_Ledger/assets/127795314/35a9b65c-89b2-4fe7-ac38-6d60db4870a0">

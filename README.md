# AML-Data
NOTE:  Although this Github repository is under the Apache-2.0 license, the actual data is released under the [CDLA-Sharing-1.0 license](https://spdx.org/licenses/CDLA-Sharing-1.0.html).

**DATA:**  https://ibm.box.com/v/AML-Anti-Money-Laundering-Data

**[PDF DOCUMENTATION](https://ibm.box.com/v/AML-Anti-Money-Laundering-Data/file/780515045707)**

The data represents financial transactions -- bank transfers, purchases, credit card transactions, checks, etc.  Most of the transactions are legitimate.  A few represent money laundering.  The data is in CSV format.

The data is generated using a multi-agent virtual world model.  All of the agents in the virtual world have actions governed by statistical distributions.  Thus the model and data are NOT based on obfuscating or anonymizing real individuals.  Everything is synthetic.  More specifically the underlying model uses a virtual world of banks, individuals, and companies -- with individuals and companies buying items, and doing bank transfers to make payments, get supplies, pay salaries, etc.  The underlying model has good and bad actors, with bad actors doing things like smuggling, extortion, illegal gambling, etc.  The bad actors sometimes attempt to launder ill-gotten funds resulting in money-laundering transactions.  

**RELATED WORK**
* Alternate AML Data and Models:  https://github.com/IBM/AMLSim 
     * Focus on models
     * Data generation does not use detailed virtual world approach used here

* Synthetic credit card transaction data:  https://github.com/IBM/TabFormer 
     * Labeled for fraud / not-fraud
     * Github site contains both data and Transformer-based fraud detection model

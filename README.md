# GST-Data-Analysis-Using-Python

# Background:

Improving the state’s ability to tax effectively is increasingly seen as central to the development process. With an expanded taxpayer base following the introduction of 
the Goods and Services Tax (GST) across India in 2017, increasing compliance and reducing tax evasion continue to be significant challenges for state governments. One 
prevalent mode of evasion involves bogus firms - a company that exists only on paper to provide tax credits to other firms - helping genuine firms suppress actual tax liability. You will be working on a dummy transactions dataset between firms and their trading partners. Some of the firms in this dataset have been identified by the partnering tax department as bogus (or fraudulent). In this test, you will have to methodically follow the given instructions to clean and prepare the dataset for modeling, i.e., generating predictions on other potentially fraudulent firms based on the available information.

# Dataset:

A typical dealer registered under the Goods and Services tax has to file a GSTR-1/B2B return at the end of every filing period. In this return, the dealer is liable to declare the details of every sale and the tax owed on that sale. The tax owed (central GST, state GST or integrated GST, as applicable) is calculated as a percentage of taxable value of the items sold according to the rate applicable on the goods. At the end of the filing period, the dealer is liable to pay the sum total of the tax owed on every sale, to the government.This is a sample dataset of transactions declared by a number of seller firms. The identifiers for firms and their trading partners (GSTINs) are encrypted, and all other information on variables have been described in detail below:

# You have been provided with two different datasets:
1. **Firms:** It provides a firm identifier (GSTIN) and an indicator on whether the firm has been found to be bogus from past inspections results.
2. **Transactions:** It provides GSTINs of seller and purchaser, filing period (MMYYYY) of when the transaction was reported, invoice number, invoice date, quantity of 
items, rate of tax, amount of tax by type (integrated tax, central tax, state tax, cess). Please refer to the sheet ‘Codebook’ in the Transactions file for a clearer 
description of the variables.

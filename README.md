# my_final_year_project
GST predictive analysis 


Attribute Name	   ------Importance in Fraud Detection
1.GSTIN   - 	Used to uniquely identify taxpayers; essential for matching records and checking for duplicates or invalid entries.
2.Business Name    -	Helps in identifying shell companies or repeated names with different GSTINs.
3.PAN Number	  - PAN-GSTIN linkage helps detect multiple GSTINs linked to the same PAN—possible red flag for tax evasion.
4.Business Type	  -  Patterns of fraud might differ by type (e.g., shell companies might pose as Sole Proprietorships).
5.Industry Type  -	Certain industries are more prone to fraud; analyzing industry-wise trends can highlight anomalies.
6.Invoice Number	-  Duplicate or non-sequential invoice numbers are a common sign of fake invoicing.
7.Invoice Date - Helps detect backdated/future-dated invoices which are red flags.
8.Invoice Amount -	High-value invoices with no matching GST paid could indicate manipulation.
9.Taxable Amount -	If taxable amount is unusually low compared to invoice value, could be misreporting.
10.GST Rate (%)	- Misapplication of GST rate can be fraudulent; eg: charging 5% instead of 28%.
11.CGST/SGST/IGST Amounts-	Cross-check these for correctness; mismatches may indicate manipulated invoices.
12. Total GST Amount	- Should align with rate * taxable amount; deviations can help flag anomalies.
13 . ITC Claimed	- If Input Tax Credit is claimed on non-existent purchases, it’s a major fraud sign.
14. Output Tax Payable	-  Helps determine under-reporting of sales.
15. ITC Utilization	  - Excessive utilization could mean inflated purchases to reduce tax liability.
16. Net Tax Paid	-  If very low despite high sales, could be suspicious.
17. GSTR-1 -   Filed Date	Late filing could indicate delay tactics; compare with GSTR-3B for mismatches.
18 .GSTR-3B   - Filed Date	Filing mismatch between GSTR-1 and 3B is a known red flag for fraud.



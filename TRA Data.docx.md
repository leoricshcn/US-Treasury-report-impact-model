The objective is to create a datasets of bond issuance announcements. The output should be a csv file with the following columns:

- Quarter\_year: quarter and year to which the refinancing announcement refers to (e.g., Q3 2025\)  
- Date: date of the refinancing announcement in yyyy-mm-dd day format (e.g., 2025-09-17)  
- Security\_type: the type of security to be issued, could be BILL, NOTE, BOND, TIPS, SAVINGS, FRN  
- Maturity: the maturity of the security in UNITS (see next)  
- Units: the unit of measure of the maturity, could be DAYS, WEEKS, MONTHS, YEARS  
- Auction\_month: month and year of the security auction in yyyy-mm format (e.g., 2025-10)  
- Auction\_date: date of the auction in yyyy-mm-dd format (e.g., 2025-10-12)  
- Offered\_amount: the amount being issued (in billions of dollars)  
- Data\_type: could be RECOMMENDATION\_FOR\_THIS\_REFUNDING, HISTORICAL\_REFERENCE, INDICATIONS\_FOR\_NEXT\_REFUNDING   
- Notes: Any notes that are helpful interpreting or verifying the data

Data, in general, are here: [https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding/quarterly-refunding-archives](https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding/quarterly-refunding-archives)

Specific sources are:

- Financing Tables: [https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding/quarterly-refunding-archives/tbac-recommended-financing-tables-by-calendar-year](https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding/quarterly-refunding-archives/tbac-recommended-financing-tables-by-calendar-year)  
- TBAC Reports: [https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding/quarterly-refunding-archives/treasury-borrowing-advisory-committee-report-to-the-secretary-by-calendar-year](https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding/quarterly-refunding-archives/treasury-borrowing-advisory-committee-report-to-the-secretary-by-calendar-year)  
- Official Remarks: [https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding/quarterly-refunding-archives/official-remarks-on-quarterly-refunding-by-calendar-year](https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding/quarterly-refunding-archives/official-remarks-on-quarterly-refunding-by-calendar-year)   
- Other documents as needed

As a first step, please collect data for the following quarters:

- Q2 2025  
- Q1 1990  
- Q3 2001  
- Q4 2012


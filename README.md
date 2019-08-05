# Personal Finance Spreadsheet
Matthew Calligaro\
Summer 2019

## Summary
This repository contains an Excel workbook which has been designed to help users track personal finances and investments.  The workbook contains regions for input (such as transactions) and regions with automatic calculations to help summarize and visualize trends in your finances.

I created this spreadsheet for personal use, and I am sharing it because I hope it will help others manage their money and achieve their financial goals.  I have done my best to make the spreadsheet "just work" for those unfamiliar with Excel, but if you are familiar with Excel, I encourage you to adjust the layout and formulas to best suit your needs. 

All of the sheets of the workbook are protected, which prevents users from accidentally breaking the formulas.  **For the general use case, you should not need to unprotect any sheets**.  If you would like to make changes or add new features, you will likely need to unprotect certain sheets.  Do note that many of the formulas are complex and highly interdependent, so be careful when making changes.  

## Disclaimer
* This spreadsheet is simply a tool to aid you in tracking your finances; it should **not** be construed as legal, financial, or tax advice.  
* The formulas in the spreadsheet may contain errors, and I am not liable for any issues that arise from incorrect calculations.  
* The formulas in this spreadsheet have been extended to 10 years.  If you record more than 10 years of data, you will need to manually extend some formulas.

## Table of Contents
The workbook contains the following sheets:
1. **Instructions**: the contents of this `README`.
2. **Transactions**: a place to record transactions; tracks the current balance in liquid accounts.
3. **Investments**: a place to record the monthly balance in investment accounts; tracks trends and growth in investment accounts.
4. **MonthlyReport**: a monthly summary of financial activity, including trends in accounts and breakdown of transactions by categories.
5. **AnnualReport**: an annual summary of financial activity, including trends in accounts and breakdown of transactions by categories.
6. **Categorical**: a pivot table aggregating transactions by categories and subcategories.
7. **Charity**: a place to record charitable donations; tracks annual summaries and all time contributions per charity.
8. **PlannedPurchases**: a place to record upcoming large purchases.
9. **Graphs**: plots trends in wealth, investment accounts, expenses, etc. on a monthly basis.
10. **Config_Categories**: allows the user to specify categories and subcategories which are used throughout the workbook.
11. **Config_Accounts**: allows the user to specify liquid and investment accounts which are used throughout the workbook.

The first column (`Column A`) of each sheet contains instructional information, including explanations of each column of that sheet.

## Getting Started
For the best experience, I recommend that you take the following steps when first using this workbook:
1. Find a safe place to store `PersonalFinance.xlsx`.  You may wish to keep it in a Git repository for versioning, but you may wish to copy the file elsewhere so the contents of the file are not tracked.
2. The first column (`Column A`) of each sheet contains instructional information about that sheet. Skim through the first column of each sheet to familiarize yourself with the workbook.  
2. Look through the `Config_Categories` sheet and add any categories or subcategories that you would like.
3. In the `Config_Accounts` sheet, fill in the information about your liquid and investment accounts.
4. In the `Transactions` sheet, fill in the starting balance for each of liquid account on `Row 3` as instructed. 
5. In the `Investments` sheet, fill in the current balance and total contribution for each investment account on `Row 3` as instructed.
6. Use some method to protect and encrypt your workbook.  You can add a password in Excel under `File -> Protect Workbook` or use an external encryption method. 


After getting set up, track your finances by doing the following:
* Record all transactions in the `Transactions` sheet as instructed.  I find it easiest to keep my receipts and input my transactions once per week, which takes roughly 5-10 minutes per week. 
* On the last day of each month, fill in the balance and contribution to each investment account in the `Investments` sheet as instructed.  Look over the `MonthlyReport` and verify the actual balance in each liquid account against the `MonthlyReport`.  Investigate any discrepancies.  I find that this takes roughly 10-20 minutes per month.  

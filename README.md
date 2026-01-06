# Recent Trends in the Treasury Market

This repository includes the excel workbooks used to create the charts for my post about recent trends in the market for U.S. Treasury securities (found [here](https://j-r-stevenson.github.io/projects-page/treasury2025review.html)). With the exception of notesbonds_auction_data, bills_auction_data, and combinedauctiondata, all workbooks were created from transformations and/or combinations of csv files from either the St. Louis Fed's FRED or the Treasury Department. The combinedauctiondata workbook was conceived after the notesbonds_auction_data and bills_auction_data workbooks were already completed, otherwise it would not have been necessary to create them. These three workbooks came from csv files created in Python after obtaining jsons through a Treasury Department API (https://fiscaldata.treasury.gov/api-documentation/). 

Some charts are still present in the workbooks uploaded. However, several pivot tables produced multiple charts, and in each case only one of the charts so created are present in the uploaded workbooks. In each case, all charts in the original post (not already attributed to another source) should be reproducible from the workbooks below.*  

*Two exceptions are the ACM term premium chart is just a simple chart created from a workbook accessible here (https://www.newyorkfed.org/research/data_indicators/term-premia-tabs#/interactive)

Here are the relevant workbooks for each section of the post:

Headline Figures on the National Debt

FederalSurplusDeficitGDP.xlsx

InterestOutlays.xlsx

InterestToGDP.xlsx

totaldebtoutstanding.xlsx



Yields

dailyparyields.xlsx


Auctions

bills_auction_data.xlx

combinedauctiondata.xlsx

notesbonds_auction_data.xlsx

InvestorClassBills.xls

InvestorClassCoupons.xls


Foreign Ownership 

TICData.xlsx


Maturity

combinedauctiondata.xlsx

totaldebtoutstanding.xlsx


Fed Balance Sheet

bills_auction_data.xlsx

FedHoldings.xlsx

notesbonds_auction_data.xlsx


Fed Funds and Long-term Yields

YieldsFedFunds.xlsm

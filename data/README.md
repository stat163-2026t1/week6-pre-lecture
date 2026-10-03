# Data source and licence

Both files are unmodified row subsets of:

**Online Retail II**, UCI Machine Learning Repository,
https://archive.ics.uci.edu/dataset/502/online+retail+ii

Real transactions (2009-12-01 to 2011-12-09) of a UK-based, registered, non-store online
retailer. Licensed under **CC BY 4.0**. UCI publishes it as an Excel workbook with one
sheet per year.

- `online_retail_2010_11.csv`: all rows with `InvoiceDate` in November 2010.
- `online_retail_2010.xlsx`: two sheets, `2010-11` (the same rows) and `2010-12` (all rows
  with `InvoiceDate` in December 2010, from the sheet `Year 2010-2011`). The values are
  written as the original workbook stores them, a number or a text in each cell.

https://www.convertcsv.com/xml-to-csv.htm
for online conversion -- doesn't work, complete mess

Converting XML to CSV via python
didn't work, complete mess of a data_dict

Import of data_dict strings into excel,
complete mess

***THE FOLLOWING WORKED*******
copy the spreadsheet elements on the page https://www.treasury.gov/resource-center/data-chart-center/interest-rates/Pages/TextView.aspx?data=yieldAll
open a blank excel workbook
in cell A1, ctrl-V (paste) the copied elements from the clipboard
save file as yieldCurve.csv in the folder Data-RAW-YieldCurve

Move to the Data-LATEST when you are satisfied is has all the latest information

The script for the YieldCurve assumes you have all the years since the beginning of the file on the web which is 01/02/1990 (January 2nd) and will get rid of those
rows that are not germain to the VX analysis.


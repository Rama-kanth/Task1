For removing null values i follow these steps:
a.Select the column or range.
b.Press F5 (or Ctrl + G) → Click "Special"
c.Select "Blanks" → Click OK.
d.Excel will highlight blank cells. Right-click → Delete → Choose "Shift cells up" 

For removing Duplicates i follow these steps:
a.Select your data.
b.Go to the "Data" tab.
c.Click "Remove Duplicates".
d.In the popup, check the columns you want to check for duplicates
e.Click OK — Excel will remove duplicates and tell you how many were removed.

For removing inconsistent formats i follow these steps:
 1. Remove Extra Spaces
    =TRIM(A2)
2. Fix Capitalization (Proper/Lower/Upper Case)
   =PROPER(A2)
   =LOWER(A2)
   =UPPER(A2)
3. Convert Numbers Stored as Text to Numbers
   =VALUE(A2)
4. Standardize Date Formats
   =TEXT(A2, "yyyy-mm-dd")

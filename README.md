My goal was to clean The Nashville Housing data to make it more user friendly for analysis. I achieved this by:
1) Changing the date format to a standardized version
2) I cleaned the Address column as there were duplicates. I did this by using the JOIN query to identify the duplicates and updated it. I also broke out the PropertyAddress column into two main columns to make it easier to analyze
3) I cleaned the OwnerAddress by also spliting it into two columns. Similar to whati did with the propertyAddress
4) Some SoldAsVacant columns had inconsistent data so i had to change it from Y and N to Yes and No
5) There were over 120 dublicate rows. so i used the ROW_NUMBER() to identify and remove those rows
6) I finally deleted unued columns from the OwnerAddress, TaxDistrict and PropertyAddress columns so analyzing could be done easily.

Alltogether, it was incredible to see just how data cleaning is essential for the job of analyzers.

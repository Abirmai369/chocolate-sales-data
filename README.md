# chocolate-sales-data
📁 Dataset Used:
 chocolate-sales-data

1. **Removed Duplicate Rows**  
   - Used Excel's "Remove Duplicates" under the **Data** tab to eliminate any repeated customer records.
   - 
2. **Handled Missing Values**  
   - Identified blank cells using **Go To → Special → Blanks**.
   - Deleted rows with missing data to ensure completeness.

3. **Standardized Text Values**  
   - Gender values were standardized using **Find & Replace**:
     - Changed `"male"` to `"Male"`
     - Changed `"female"` to `"Female"`

4. **Converted Date Format**  
   - The `Date&year` column was converted to a consistent date format: `dd-mm-yyyy`.
   - Column renamed to `VisitDate`.

5. **Checked and Fixed Data Types**  
   - Ensured numeric columns (`Age`, salesperson`, `Sales person`) were correctly formatted as integers.
   - Converted `VisitDate` to datetime format for consistency.

Tools Used:
- Microsoft Excel (for data cleaning)
- GitHub (for version control and submission)

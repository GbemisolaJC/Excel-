# Data Manipulation and Cleaning Using Microsoft Excel

### Text Cleaning Functions
1. **LOWER, UPPER, and PROPER**: 
   - **LOWER**: Converts all letters in a cell to lowercase. Example: `=LOWER(R4)`
   - **UPPER**: Converts all letters in a cell to uppercase. Example: `=UPPER(R4)`
   - **PROPER**: Capitalizes the first letter of each word in a cell. Example: `=PROPER(R4)`

2. **TRIM**: 
   - Removes extra spaces from the beginning, between, and at the end of a text string. Example: `=TRIM(R4)`


![text cleaning](https://github.com/user-attachments/assets/3fa89140-f090-40a0-ad87-e738e62ebd31)


## Text Extraction in Excel

1. **Using the LEFT Function**  
   Use the `LEFT` function to retrieve text from the beginning of a cell's content.  
   Example: If cell R4 contains "151410031220", to extract the first 4 characters:  
   `=LEFT(R4, 4)`  // Result: "1514"

2. **Using the RIGHT Function**  
   Use the `RIGHT` function to retrieve text from the end of a cell's content.  
   Example: If cell R4 contains "151410031220", to extract the last 4 characters:  
   `=RIGHT(R4, 4)`  // Result: "1220"

3. **Using the MID Function**  
   Use the `MID` function to extract text from the middle of a cell's content.  
   Example: If cell R4 contains "151410031220", to extract "4100" starting from the 3rd character for 4 characters:  
   `=MID(R4, 3, 4)`  // Result: "4100"

![image](https://github.com/user-attachments/assets/475d29c3-079f-4985-92fa-d4c595a78a72)



### Data Summarization Using Excel Functions
1. **SUM**: Adds up all values in the selected range. Example: `=SUM(A1:A10)`
2. **MAX**: Returns the maximum value within the selected range. Example: `=MAX(A1:A10)`
3. **MIN**: Returns the minimum value within the selected range. Example: `=MIN(A1:A10)`
4. **LARGE**: Returns the top 'x' largest values within the selected range. Example: `=LARGE(A1:A10, k)` where `k` is the position of the value.
5. **AVERAGE**: Calculates the average of the selected values. Example: `=AVERAGE(A1:A10)`
6. **COUNT**: Counts the number of entries in a numeric field within a range. Example: `=COUNT(A1:A10)`
7. **COUNTA**: Counts the number of non-blank entries (text or numbers) in the selected range. Example: `=COUNTA(A1:A10)`


![image](https://github.com/user-attachments/assets/2b377c77-ee04-4371-9ddb-82a05b46d7ab)

# Lumen RPA Challenge
## @DeltaD32 - March 5 2023
### Process List

1. **Func_ConfigSetupandChecks** 
    - Checks Chrome downloaded
        - if not installed, fails
    - Checks Excel Installed
        - If not installed, navigates to office.com and fails
    - Checks if Chrome windowss are already open
        - If found, loops through closing all windows until none remain.
    - Checks Chrome Download Folder Location is Same as expected
        - if not same, assigns download location to custom location already existing
    - Navigates to Exercise page and downloads workbook from site to minimize errors
        - Waits for download and when finished, moves file to **_"C:\temp\Exercise.xlsx "_** to standardize
    - Establishes **_"rpachallenge.com"_** as Default URL location

2. **Comp_ExerciseExecute**
    - Establishes working data table from downloaded Excel File
    - Grabs Headers for use in Loop
    - Loops Through each Data Table row and each column header
        <br><img src="https://github.com/DeltaD32/Lumen_RPA_CHALLENGE/blob/main/Challenges/Lumen%20Challenge/Form_ENTRY/Loop%20Screenshot.png?raw=true" width="300"><br>
        - Gets ID Attribute for each column header that matches Entry Fields.
        - Types Column value into Field with ID Number grabbed from previous step 
        - Validates data table value entered into field matches row value. 
    - Once Loop is complete, grabs execution results and performs math on time to present in message box. 
    

    

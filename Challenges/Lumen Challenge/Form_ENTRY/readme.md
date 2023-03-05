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
    _
    
    
# Step 1
- Complete *At least* 3 successful salt slugs during storm and 3 during base flow.
  - Each of these needs to have:
    - Date
    - Start Time
    - End Time
    - Reach length
    - Salt mass
  - The conductivity data of these slugs can be put in a seperate folder with the information
# Step 2
  - Using an R/Python script we can use the tracer_discharge.xlsx to calculat the discharge for each of these slugs
  - After calculation of discharge, they can be be written to a new CSV file containing:
    - Date
    - Start Time
    - End Time
    - Site
    - Discharge
# Step 3
  - Using the `dataRetrieval` R package, download the 
  - After matched up 
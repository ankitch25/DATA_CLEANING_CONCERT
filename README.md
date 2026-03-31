# DATA_CLEANING_CONCERT
# Highest-Grossing Female Concert Tours
This Excel project cleans and restructures a ranked dataset of major female concert tours into an analysis-ready format.
## Project summary
The workbook starts from a source-style table and transforms it into a cleaner working dataset with normalized headers, numeric gross fields, simplified year values, and a small lookup dashboard for artist-level analysis.
## Cleaning steps
 - Standardized column names for consistency
 - Converted currency-like text fields into numeric values
 - Removed source artifacts such as footnotes and special symbols from key text fields
 - Simplified year labels for easier filtering and comparison
 - Preserved explicit missing-value labels where data was not available
## Output
The cleaned sheet supports formula-based analysis of each artist’s best adjusted-gross tour using Excel lookup functions.
The workbook uses combinations of `INDEX`, `MATCH`, and `MAXIFS` to retrieve the highest adjusted-gross record for the selected artist.
</>

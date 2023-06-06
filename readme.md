# Regex Expert for Cleaning Text Strings

To extract meaningful information from the csv and understand the extent of manual cleaning required, you can use regular expressions (regex) and apply data science techniques.

1. Data Cleaning:
- Remove leading and trailing whitespaces from the composition strings.
- Convert all text to lowercase for consistency.
- Remove any special characters or punctuation that are not meaningful for the analysis.

2. Tokenization:
- Split the composition strings into individual tokens using whitespace or specific separators like "%", "+", etc. This will separate the different components of the composition.

3. Parsing and Extraction:
- Define patterns using regex to identify and extract relevant information from the composition strings.
- Create regex patterns for common composition formats like "% material_name" or "percentage% material_name".
- Use regex capture groups to extract the percentage and material name separately.

4. Cleaning extracted information:
- Standardize the material names by mapping them to a common format (e.g., "cotton" instead of "COTTON").
Remove any additional qualifiers or descriptors that are not relevant to the analysis (e.g., "knitted," "woven," "excluding trims," etc.).

5. Data Analysis:
- Calculate statistics on the extracted information, such as the percentage distribution of different materials or the frequency of specific material combinations.

6. Automation:
- Based on the analysis, identify patterns and variations in the composition strings that require manual cleaning.
- Determine rules or heuristics to automate the cleaning process for common patterns.
- For more complex or irregular cases, consider a semi-automated approach where manual intervention is required but assisted by pre-defined rules or machine learning algorithms.

7. Recommendation:
- Evaluate the accuracy and reliability of the automated or semi-automated cleaning method on a subset of the data.
- Based on the results, assess the feasibility and efficiency of implementing the method for the entire dataset.
- Consider the resources and time required for maintaining and updating the cleaning process as new variations or patterns emerge.

By following this approach, we can extract meaningful information from the composition strings, automate or semi-automate the cleaning process, and gain insights into the material compositions of different products.

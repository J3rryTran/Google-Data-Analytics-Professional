# Process Data from Dirty to Clean  
## Data cleaning  

- Dirty Data: Data that is incomplete, incorrect, or irrelevant. It can contain errors, repetitions (duplicates), blank fields (nulls), or inconsistent formats, making effective analysis difficult or impossible.
- Clean Data: Data that is complete, correct, and relevant to the problem being solved. It is the foundation for identifying patterns, drawing useful conclusions, and making effective decisions.

## Roles and Responsibilities:
- Data Engineers and Data Warehousing Specialists are professionals who help ensure data quality by transforming, storing, and organizing it.   
- Data that comes from internal systems managed by these professionals is more likely to be clean.
- However, the passage stresses that no dataset is perfect, and data analysts are still ultimately responsible for examining and cleaning their data before analysis, regardless of the source.

**Practical Examples of Data Cleaning:**   
- Internal Data - Handling Duplicates: When counting unique software users, an analyst might find that one person has multiple usernames. The data must be cleaned by removing these duplicate entries to get an accurate count.

External Data - Handling Nulls: When analyzing survey data, an analyst might encounter "nulls" (missing values where a question was skipped). A null is different from a zero. The analyst must decide how to handle these nulls:

Filter them out and report the analysis on a smaller sample size.

Keep them in and analyze why the questions were skipped, which could reveal issues with the survey design itself (e.g., confusing or biased questions).

The core message is that data cleaning is an essential step in the analysis process, especially when working with external data from multiple sources, to ensure the integrity and reliability of any findings.

**Common dirty data**   
- Duplicate data
- Outdate data
- Incomplete data
- Incorrect/inaccurate data
- Inconsistent data   

**Common data-cleaning pitfalls**   
- **Not Checking for Spelling Errors**: 
Simple typos or variations in spelling (especially for names and addresses) can create duplicate records and skew analysis, as they often aren't caught by standard spellcheck tools. **Example**,  customer database contains entries for both "John Smith" and "Jon Smith," who are the same person. If this isn't corrected, analyses on customer counts or purchase history will be inaccurate.

- **Forgetting to Document Errors**:
Failing to keep a log of errors and their solutions wastes time, as you have to troubleshoot the same problem repeatedly. Documenting fixes creates a reference guide for future issues and helps track changes. **Example**, you discover a spreadsheet formula breaks because some dates are formatted as `MM-DD-YY` while others are `DD-MM-YYYY`. By documenting this issue and the fix, the next time a similar error occurs, you can resolve it immediately instead of investigating from scratch[1].

- **Not Checking for Misfielded Values**:
This occurs when data is entered into the wrong field or column. It's hard to detect because the value itself might be valid, just misplaced. **Example**, in a customer contact list, the value "Spain" is mistakenly entered into the "City" column instead of the "Country" column. An analysis to find all customers in the country of Spain would then miss this record completely.

- **Overlooking Missing Values**:
Gaps or nulls in a dataset can lead to incomplete analysis and inaccurate conclusions, especially for calculations like totals or averages. **Example**, you are calculating the average monthly revenue for a product. If sales data for several days is missing, the calculated average will be artificially low and misleading.

- **Only Looking at a Subset of the Data**:
Focusing on just one part of the data can cause you to miss systemic issues, like duplicates, that only become apparent when looking at the complete picture. **Example**, you are merging customer lists from two different company branches. If you only clean one list before merging, you won't identify customers who exist on both lists, resulting in duplicate entries in the final dataset.

- **Losing Track of Business Objectives**:
It's easy to get distracted by interesting but irrelevant findings in the data. This can waste time and lead you away from the original question you were trying to answer. **Example**, while cleaning sales data to identify the top-selling product, you notice an unusual purchasing pattern from a specific city. Investigating this pattern is not part of the original task and should be set aside until the primary objective is met.

- **Not Fixing the Source of the Error**:
It is inefficient to only fix individual errors without addressing the underlying cause. The problem will continue to reappear until the root cause is resolved. **Example**, a web form allows users to enter their phone number as free text, resulting in inconsistent formats (`(555)-123-4567`, `555.123.4567`, `5551234567`). Instead of repeatedly cleaning this data, the better solution is to update the web form to enforce a single input mask, fixing the error at its source.

- **Not Analyzing the System Prior to Cleaning**:
Jumping into cleaning without understanding the root cause of the errors is like fixing a car without a diagnosis. You must first understand where the bad data originates to clean it effectively and prevent it from happening again. **Example**, you find many errors in a customer database. Before cleaning, you investigate and learn that the errors come from a faulty data import script that misaligns columns. Knowing this, you can focus on fixing the script, which is more effective than just manually correcting the current data.

- **Not Backing Up Data Prior to Cleaning**:
Cleaning data involves making permanent changes. Without a backup, a mistake or program crash could lead to irreversible data loss. **Example**, before running a script to delete thousands of duplicate records, you save a copy of the original file. The script accidentally deletes valid records, but because you have a backup, you can restore the original data and fix the script without any permanent damage.

- **Not Accounting for Data Cleaning in Deadlines**: 
Data cleaning is a time-consuming but critical part of any data project. Failing to allocate time for it in your project schedule will lead to inaccurate timelines and missed deadlines. **Example**, when planning a project, a manager gives you two days for analysis. You should explicitly state that the first day (or a portion of it) will be dedicated to data cleaning and validation, setting a realistic expectation with stakeholders for when they can see the final results.



## Verify and report data cleaning   

1. Data Verification
- What it is: Verification is the process of double-checking your cleaned dataset to confirm that the cleaning was done correctly and thoroughly. It involves reviewing the data, making any final manual corrections, and ensuring the data is still appropriate for the original project goal.
- Why it's important: Verification is critical because it helps you catch small but significant errors (like a forgotten semicolon or a typo) before you begin analysis. Without this step, the insights from your analysis would be untrustworthy, potentially leading to bad business decisions or misrepresenting populations.

2. Reporting on Data Cleaning
- This involves documenting and communicating your data cleaning efforts to your team and stakeholders.

- Reporting builds trust and accountability. It ensures transparency by showing exactly what changes were made to the data, which keeps everyone on the same page regarding important project details.

- You can report on your work through:
    - Data-cleaning reports: Formal summaries of the cleaning activities.
    - Documenting the process: Keeping notes on the steps taken.
    - Using a changelog: A chronologically ordered file that lists all modifications made to a project (e.g., features added, improved, or removed), often organized by date or version. This provides a clear history of how the dataset has evolved.   

3. Confirm data cleaning 
- Tactical Comparison with Original Data:
    - Action: Go back to the dirty data and identify the original problems (e.g., nulls, misspellings, formatting issues).
    - Verification: Use tools like filters or search functions to confirm that these specific errors no longer exist in the clean dataset. For example, if a product name was commonly misspelled, you would search the clean data to ensure no instances of that misspelling remain.   

- Big-Picture Strategic Review
    - Revisit the Business Problem: Confirm that the analysis is still focused on solving the original business problem. It's easy to get sidetracked by other interesting findings, but you must ensure the data is being used to answer the primary question.
    - Revisit the Project Goal: Go beyond the problem to understand the purpose of the analysis. For example, the goal isn't just to analyze customer feedback but to use it to improve a product. You must confirm that your cleaned data will actually help achieve that specific goal.
- Reassess the Data's Capability:
    - Sanity Check: Step back and ask, "Do the numbers make sense?" For example, if a survey was sent to 1,000 people but you have more than 1,000 responses, this is a red flag that something is wrong (e.g., duplicates, system error).
    - Get a Fresh Perspective: Ask a teammate to review your data. A fresh pair of eyes can help catch errors or assumptions that you might miss due to being too familiar with the dataset.
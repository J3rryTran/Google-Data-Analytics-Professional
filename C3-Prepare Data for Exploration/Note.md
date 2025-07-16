# Data formats in practice

### Primary versus secondary data

The following table highlights the differences between primary and secondary data and presents examples of each.

| Data format classification | Definition | Examples |
| :--- | :--- | :--- |
| **Primary data** | Collected by a researcher from first-hand sources | - Data from an interview you conducted<br>- Data from a survey returned from 20 participants<br>- Data from questionnaires you got back from a group of workers |
| **Secondary data** | Gathered by other people or from other research | - Data you bought from a local data analytics firm's customer profiles<br>- Demographic data collected by a university<br>- Census data gathered by the federal government |

### Internal versus external data

The following table highlights the differences between internal and external data and presents examples of each.

| Data format classification | Definition | Examples |
| :--- | :--- | :--- |
| **Internal data** | Data that is stored inside a company's own systems | - Wages of employees across different business units tracked by HR<br>- Sales data by store location<br>- Product inventory levels across distribution centers |
| **External data** | Data that is stored outside of a company or organization | - National average wages for the various positions throughout your organization<br>- Credit reports for customers of an auto dealership |

### Continuous versus discrete data

The following table highlights the differences between continuous and discrete data and presents examples of each.

| Data format classification | Definition | Examples |
| :--- | :--- | :--- |
| **Continuous data** | Data that is measured and can have almost any numeric value | - Height of kids in third grade classes (52.5 inches, 65.7 inches)<br>- Runtime markers in a video<br>- Temperature |
| **Discrete data** | Data that is counted and has a limited number of values | - Number of people who visit a hospital on a daily basis (10, 20, 200)<br>- Maximum capacity allowed in a room<br>- Tickets sold in the current month |

### Qualitative versus quantitative data

The following table highlights the differences between qualitative and quantitative data and presents examples of each.

| Data format classification | Definition | Examples |
| :--- | :--- | :--- |
| **Qualitative** | A subjective and explanatory measure of a quality or characteristic | - Favorite exercise activity<br>- Brand with best customer service<br>- Fashion preferences of young adults |
| **Quantitative** | A specific and objective measure, such as a number, quantity, or range | - Percentage of board certified doctors who are women<br>- Population size of elephants in Africa<br>- Distance from Earth to Mars at a particular time |

### Nominal versus ordinal data

The following table highlights the differences between nominal and ordinal data and presents examples of each.

| Data format classification | Definition | Examples |
| :--- | :--- | :--- |
| **Nominal** | A type of qualitative data that is categorized without a set order | - First time customer, returning customer, regular customer<br>- New job applicant, existing applicant, internal applicant<br>- New listing, reduced price listing, foreclosure |
| **Ordinal** | A type of qualitative data with a set order or scale | - Movie ratings (number of stars: 1 star, 2 stars, 3 stars)<br>- Ranked-choice voting selections (1st, 2nd, 3rd)<br>- Satisfaction level measured in a survey (satisfied, neutral, dissatisfied) |

### Structured versus unstructured data

The following table highlights the differences between structured and unstructured data and presents examples of each.

| Data format classification | Definition | Examples |
| :--- | :--- | :--- |
| **Structured data** | Data organized in a certain format, like rows and columns | - Expense reports<br>- Tax returns<br>- Store inventory |
| **Unstructured data** | Data that cannot be stored as columns and rows in a relational database | - Social media posts<br>- Emails<br>- Videos |


## The effects of different structures
- **Structured data**: Organized in a certain format, such as rows and columns.
- **Unstructured data**: Not organized in any easy-to-identify way.    

| **Structured Data** | **Unstructured Data** |
| :--- | :--- |
| - Defined data types | - Varied data types |
| - Most often quantitative data | - Most often qualitative data |
| - Easy to organize | - Difficult to search |
| - Easy to search | - Provides more freedom for analysis |
| - Easy to analyze | - Stored in data lakes, data warehouses, and NoSQL databases |
| - Stored in relational databases & data warehouses | - Can't be put in rows and columns |
| - Contained in rows and columns | - **Examples:** Text messages, social media comments, phone call transcriptions, various log files, images, audio, video |
| - **Examples:** Excel, Google Sheets, SQL, customer data, phone records, transaction history | |    

## Data modeling levels and techniques
**Data modeling** is the process of creating visual diagrams, called data models, to represent how data is structured and organized. The passage compares a data model to a blueprint for a house. Just as various builders like carpenters and electricians use the same blueprint to understand the overall structure of the house for their different jobs, different data users use a data model to get a common understanding of the data's structure as a whole, even though they may have different individual needs.   

### The three most common types of data modeling
1. **Conceptual data modeling** gives a high-level view of the data structure, such as how data interacts across an organization. For example, a conceptual data model may be used to define the business requirements for a new database. A conceptual data model doesn't contain technical details. 
2. **Logical data modeling** focuses on the technical details of a database such as relationships, attributes, and entities. For example, a logical data model defines how individual records are uniquely identified in a database. But it doesn't spell out actual names of database tables. That's the job of a physical data model.
3. **Physical data modeling** depicts how a database operates. A physical data model defines all entities and attributes used; for example, it includes table names, column names, and data types for the database.    

## Explore data types, fields, and values
### Transforming data
Data transformation is the process of changing the data’s format, structure, or values. As a data analyst, there is a good chance you will need to transform data at some point to make it easier for you to analyze it.    
Data transformation usually involves:
- Adding, copying, or replicating data 
- Deleting fields or records 
- Standardizing the names of variables
- Renaming, moving, or combining columns in a database
- Joining one set of data with another
- Saving a file in a different format. For example, saving a spreadsheet as a comma separated values (.csv) file.   

Goals for data transformation might be: 
- Data organization: better organized data is easier to use
- Data compatibility: different applications or systems can then use the same data
- Data migration: data with matching formats can be moved from one system to another
- Data merging: data with the same organization can be merged together
- Data enhancement: data can be displayed with more detailed fields 
- Data comparison: apples-to-apples comparisons of the data can then be made    

## Bias Data
Bias is when a sample isn't representative of the population as a whole. Sampling bias occurs when a data sample is not representative of the larger population, leading to skewed results. This happens when the sample isn't chosen randomly, causing certain parts of the population to be favored over others.
- Cause: Non-random sampling.
- Solution: Use random sampling to ensure every member of the population has an equal chance of being selected.
- Example: Surveying only the first 10 students (who all happen to be women) to draw conclusions about an entire class of 50 students with diverse genders.
- Detection Method: Use visualizations, like bar charts, to compare the characteristics of your sample to the characteristics of the overall population to easily spot any misrepresentation.   

Observer Bias (or Experimenter Bias): This is the tendency for different people to observe the same thing differently, leading to subjective and inconsistent data.
- Example: Two scientists looking at the same microscope slide may record different observations, or healthcare workers may round blood pressure readings up or down, affecting data precision.

Interpretation Bias: This is the tendency to interpret ambiguous situations in a positive or negative way based on personal background, experiences, and emotions.
- Example: One person interprets a boss's voicemail as angry due to their history, while a friend hears the same message as calm and straightforward.

Confirmation Bias: This is the tendency to search for, favor, and interpret information in a way that confirms one's pre-existing beliefs, while ignoring contradictory evidence.
- Example: Only getting news from sources that share your viewpoints or only noticing data points that support a gut feeling.   

### Good and bad data

The good data using the acronym ROCCC as a framework for evaluation. The goal is to ensure data is trustworthy before using it for analysis and decision-making.   
The five criteria of the ROCCC framework are:
- R - Reliable: The data is accurate, complete, unbiased, and has been vetted to ensure it is fit for use.
- O - Original: The data can be traced back to its primary source, ensuring you are not relying on potentially altered second or third-hand information.
- C - Comprehensive: The data includes all the critical information needed to answer your questions and is not missing key components.
- C - Current: The data is up-to-date and relevant to the task at hand, as the value of data often decreases over time.
- C - Cited: The source of the data is clear and credible. You should know who created the data, if they are from a reputable organization, and when the data was last updated.

Bad data is not reliable, original, comprehensive, current, or cited, and can lead to significant negative consequences.  
The characteristics of bad data, as outlined by the inverse of the ROCCC framework, are:
- **Not Reliable**: Bad data cannot be trusted because it is inaccurate, incomplete, or biased.
Example: Data may suffer from sampling bias if it doesn't reflect the overall population. Another example is a misleading data visualization, such as a bar graph with a distorted y-axis that makes small changes in interest rates appear much larger than they actually are.

- **Not Original**: If you cannot trace the data back to its original source and are relying on second or third-hand information, it is a warning sign that the data may be unreliable.

- **Not Comprehensive**: The data is incomplete, missing critical information needed to find a solution, or may contain human errors.

- **Not Current**: The data is outdated and no longer relevant to the task at hand. Reputable sources, like Data.gov, regularly refresh their data to ensure it remains current.

- **Not Cited**: If a data source has not been cited or properly vetted, it should be avoided.   
The Impact of Bad Data: using bad data can have serious and lasting negative effects, such as leading to poor business decisions or creating failed processes that put people at risk. To avoid these issues, it is essential to use good data.    

## Metadata is as important as the data itself
- File or document type: What type of file or document are you examining?
- Date, time, and creator: When was it created? Who created it? When was it last modified?
- Title and description: What is the name of the item you are examining? What type of content does it contain?
- Geolocation: If you’re examining a photo, where was it taken?
- Tags and categories: What is the general overview of the item that you have? Is it indexed or described in a specific way? 
- Who last modified it and when: Were any changes made to the file? If yes, when were the most recent modifications made?
- Who can access or update it: If you’re examining a dataset, is it public? Are special permissions needed to customize or modify it?   

### The benefits of metadata
**Reliability**
Data analysts use reliable and high-quality data to identify the root causes of any problems that might occur during analysis and to improve their results. If the data being used to solve a problem or to make a data-driven decision is unreliable, there’s a good chance the results will be unreliable as well.    
Metadata helps data analysts confirm their data is reliable by making sure it is:
- Accurate
- Precise
- Relevant
- Timely   

It does this by helping analysts ensure that they’re working with the right data and that the data is described correctly. For example, a data analyst completing a project with data from 2022 can use metadata to easily determine if they should use data from a particular file.  

**Consistency**   
Data analysts thrive on consistency and aim for uniformity in their data and databases,  and metadata helps make this possible. For example, to use survey data from two different sources, data analysts use metadata to make sure the same collection methods were applied in the survey so that both datasets can be compared reliably. 
When a database is consistent, it’s easier to discover relationships between the data inside the database and data that exists elsewhere. When data is uniform, it is:

- Organized: Data analysts can easily find tables and files, monitor the creation and alteration of assets, and store metadata. 

- Classified: Data analysts can categorize data when it follows a consistent format, which is beneficial in cleaning and processing data.

- Stored: Consistent and uniform data can be efficiently stored in various data repositories. This streamlines storage management tasks such as managing a database.   

- Accessed: Users, applications, and systems can efficiently locate and use data.   

Together, these benefits empower data analysts to effectively analyze and interpret their data.

**Metadata repositories**   
A metadata repository is a specialized database designed to store and manage metadata, which can be housed in a physical location or virtually in the cloud. Its primary function is to help data analysts ensure their data is reliable and consistent. By centralizing metadata into a common, accessible structure, these repositories offer two main benefits:
- Efficiency: They provide quick and easy access to information about data, saving analysts from the time-consuming process of manually checking each file.
- Integration: They help bring together data from multiple different sources by describing the data's origin, location, structure (e.g., tables), and user access history.

**Metadata of external databases**   
The practices data analysts when using external data, which is categorized into two types:
- Second-Party Data: Data collected directly by one group from its audience and then sold to another organization.
- Third-Party Data: Data provided by an outside source that did not collect the data itself but aggregated it from various platforms.   
The core message is that analysts must verify the quality and legitimacy of this external data before using it. The key steps are:
- Examine the Metadata: Analysts should review the metadata of external databases to ensure the information is consistent and reliable.
- Confirm Accessibility and Permissions: It may be necessary to contact the data owner to confirm that the data is available for purchase and that proper permissions to use it can be obtained.



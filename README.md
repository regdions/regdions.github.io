<div align="center">

Welcome to my portfolio! I am an Applied Mathematics graduate exploring the world of data analytics and data science. Here, I share projects where I apply my knowledge to explore real-world and academic datasets.

</div>

<br><br>

# CISCO | DATA SCIENCE WITH PYTHON COURSE PROJECTS
A collection of projects completed as part of the `Cisco Networking Academy Data Science Essentials with Python` course, covering Python programming, data manipulation, data cleaning, exploratory data analysis, and working with real-world datasets. The Projects demonstrate the practical application of Python and Data Science concepts through hands-on exercises and open-ended analyses.

<br>

## [Set 1: Coding for Answers Projects]()
This set focuses on using code to explore datasets, answer analytical questions, and extract meaningful information from data. 

1.[ First Day of Week Project ](https://github.com/regdions/CISCO-Coding-for-Answers-Projects/blob/acab8a3aeec9099ebcb9dddc05b38af0ca47758c/first-day-of-week-project/first-day-of-week-project/first-day-of-week.ipynb)

   <details>
      <summary>▷ Project Questions </summary>
         <p><pre>
• How many territories show Friday, Saturday, Sunday, and Monday as the first_day of the week?</li>
• How many people start the week on Friday, Saturday, Sunday, and Monday?</li>
• Which of the four_regions predominantly start the week on Sunday? On Monday?</li> 
• Are there any regions that are more divided between Sunday and Monday?</li>
         </pre></p>
   </details>

   <details>
      <summary>▷ Project Questions </summary>
         <ul style="padding-left: 60px; list-style-type: disc;">
            <li> How many territories show Friday, Saturday, Sunday, and Monday as the first_day of the week?</li>
            <li> How many people start the week on Friday, Saturday, Sunday, and Monday?</li>
            <li> Which of the four_regions predominantly start the week on Sunday? On Monday?</li> 
            <li> Are there any regions that are more divided between Sunday and Monday?</li>
         </ul>
   </details>

<br>

2.[ Jean Pockets Project](https://github.com/regdions/CISCO-Coding-for-Answers-Projects/tree/acab8a3aeec9099ebcb9dddc05b38af0ca47758c/jean-pockets-project/jean-pockets-project)

   Project Questions:
   - What is the average difference in pocket height_front between women's and men's jeans?
   - Is there a significant difference in pocket height_front between skinny and straight styles within the same gender?
   - How do back pocket sizes compare between women's and men's jeans?
   - What percentage of women's and men's jeans can comfortably fit your phone (15 cm) in the pockets?



4. [Largest Islands Project](https://github.com/regdions/CISCO-Coding-for-Answers-Projects/tree/acab8a3aeec9099ebcb9dddc05b38af0ca47758c/largest-islands-project/largest-islands-project)

   Project Questions:
   - What are the 10 largest islands in the tropics?
   - What are the largest islands in each region?
   - Create a line graph with area on the y-axis and rank on the x-axis. The data should be ordered by rank, from largest to smallest.
   - What islands are composed of multiple countries?



5. [Naming Colors Project](https://github.com/regdions/CISCO-Coding-for-Answers-Projects/tree/acab8a3aeec9099ebcb9dddc05b38af0ca47758c/naming-colors-project/naming-colors-project)

   Project Ideas:
   - For each language, calculate what percentage of chips are named each color. Return dataframes for each language.
   - Create a horizontal bar plot for each language. Each bar represents a color name and the length encodes the percentage of chips that are named that color.
   - Is there a correlation between languages? Create scatter plots.



6. [People on Banknotes Project](https://github.com/regdions/CISCO-Coding-for-Answers-Projects/tree/acab8a3aeec9099ebcb9dddc05b38af0ca47758c/people-on-banknotes-project/people-on-banknotes-project)

   Project Questions:
   - What proportion of individuals featured are male versus female?
   - Are writers or politicians more commonly depicted?
   - What percentage of featured individuals are musicians?
   - What percentage of banknotes were issued before the person’s death?
   - Who is the oldest historical figure in the dataset?
   - Which countries feature the oldest historical figures on their banknotes?
   - What percentage of individuals died at least 100 years before appearing on a banknote?
   - Which individuals appeared on a banknote just one year after their death?

<br>

## [Set 2: Data Cleaning Projects](https://github.com/regdions/Data-Cleaning-Projects)
Projects focused on preparing and improving datasets by identifying missing values, correcting inconsistencies, transforming data, and applying data cleaning tecniques.

1. [Emoji Sentiment Project](https://github.com/regdions/Data-Cleaning-Projects/tree/5a4c99b484d4ef072c5dbf2b43748ce34aede193/emoji-sentiment-project/emoji-sentiment-project)
   
   Data Cleaning:
   - Removed unnecessary columns that are not useful for the analysis.
   - Renamed the remaining columns using snake_case (all lowercase letters with underscores between words).
   - Added a new column called sentiment, where sentiment = (% positive tweets) - (% negative tweets).
   - Added a positive_flag column that is True if sentiment > 0 (or above a set threshold), otherwise False.
   
   Project Questions:
   - What percentage of emojis in the dataset have a positive sentiment?
   - What percentage of the top 20 most popular emojis are positive?
   - Which emoji (with more than 500 mentions) is the most positive?
   - Which emoji (with more than 500 mentions) is the most negative?
   - Where in the tweets are most emojis located (i.e. at the beginning or the end)?
   - Is there a difference in the placement of positive versus negative emojis within a tweet?



2. [Solar Eclipses Project](https://github.com/regdions/Data-Cleaning-Projects/tree/5a4c99b484d4ef072c5dbf2b43748ce34aede193/solar-eclipses-project/solar-eclipses-project)

   Data Cleaning:
   - Splitting minutes and seconds to compute for the total duration in seconds.
   - Converted Date in string data type to datetime.

   Project Questions:
   - When did the longest solar eclipse occur? The longest total eclipse?
   - What is the average duration of total solar eclipses?
   - Show the next 10 solar eclipses.



3. [Typing Speeds Project](https://github.com/regdions/Data-Cleaning-Projects/tree/5a4c99b484d4ef072c5dbf2b43748ce34aede193/typing-speeds-project/typing-speeds-project)

   Data Cleaning:
   - Remove unnecessary columns, such as PARTICIPANT_ID, to streamline the dataset.
   - Rename columns (e.g AVG_WPM_15 to wpm, ROR to ror, HAS_TAKEN_TYPING_COURSE to course) for brevity and clarity during analysis.
   
   Finger Count Analysis
   - Compare typing speeds across groups using different numbers of fingers, excluding the "10+" category for simplicity.
   - Control for consistency by first filtering to similar AGE, KEYBOARD_LAYOUT, NATIVE_LANGUAGE, KEYBOARD_TYPE, and HAS_TAKEN_TYPING_COURSE values.
   - Exclude participants with high error rates (ERROR_RATE > 3%) to focus on reliable data.
   - Drop columns after filtering if they now only have a single value.

   Rollover Ratio Analysis
   - Compare typing speeds between participants with ROR ≤ 20% and those with ROR > 80%, keeping AGE, KEYBOARD_TYPE, FINGERS, and other variables constant.
  
   Influence of Typing Course
   - Compare typing speeds between participants with a typing course (HAS_TAKEN_TYPING_COURSE = 1) and without (HAS_TAKEN_TYPING_COURSE = 0), holding other variables such as KEYBOARD_TYPE, AGE range, and FINGER_COUNT constant.
  

 
5. [Volcanic Eruptions Project](https://github.com/regdions/Data-Cleaning-Projects/tree/5a4c99b484d4ef072c5dbf2b43748ce34aede193/volcanic-eruptions-project/volcanic-eruptions-project)

   Data Cleaning
   - Converted Date from string format to datetime
   - Merged 2 dataframes
   
   Project Ideas:
   - Find the volcanoes that were erupting as of Dec 2024.
   - Find the volcanoes that have had the longest volcanic eruptions.


## [Set 3: Data Visualization Projects]()
Projects focused on exploring and communicating data through charts, graphs, and visualizations to identify patterns, trends, and meaningful insights.

1. [sample]()
2. [samoke]()
3. [sample]()



## [Set 4: Data Modeling Projects]()
Projects focused on building and evaluating statistical models in Python, including linear regression and other modeling techniques to analyze relationships and make predictions.
1. [sample]()
2. [samoke]()
3. [sample]()



## [Set 4: Data Storytelling Projects]()
This set focuses on turning data into clear and meaningful stories by combining analysis, visualizations,a nd insights to communicate findings effectively.
1. [sample]()
2. [samoke]()
3. [sample]()


<br><br>


# ONLINE RETAIL II DATA ANALYSIS PROJECT




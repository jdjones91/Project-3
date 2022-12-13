# Project 3, Final Coding Dojo Project

### In this project I performed API extraction of movie data, created a SQL database, queried that database, and performed Hypothesis Testing on 3 separate business questions for a stakeholder.

Part 1:
- Imported, cleaned, and saved databases containing specific information that the stakeholder was interested in

Part 2:
- API Extraction
  - Defined functions to locate specific information from our API call and write our information to new JSON files. Built an inner and outer loop to perform an API call for movies released in 2001 and 2002.
- EDA
  - EDA was performed in 2 separate notebooks for comparison. 1 notebook contained no additional data cleaning. The other was cleaned and organized using my best judgement pertaining to the stakeholder’s questions.

Part 3:
- Loaded in previously saved pandas DFs, concatenated multiple data frames, formatted and converted them to a SQL Database. Queries were performed to show success.

Part 4:
- API Extraction
  - A modified version of the API call built in "Part 2" was used to pull all movies released between 2009-2019. These were then written to JSON files, converted to pandas DFs, and saved.
- Hypothesis Testing
  - Pandas DFs from the API extraction notebook were loaded, cleaned, concatenated, and merged with other data frames containing additional information. 3 questions asked by the stakeholder were them put through Hypothesis testing.

### Hypothesis Testing example:

"Does the MPAA rating of a movie (G/PG/PG-13/R) affect how much revenue the movie generates?"
- Using an ANOVA Test with an Alpha = 0.05, I found that there IS a statistically significant difference in revenue generation across MPAA ratings, with PG movies grossing the highest, on average.


![Screenshot 2022-12-13 at 1 45 21 PM](https://user-images.githubusercontent.com/109368648/207439950-829a4fa3-8a05-4a9e-8186-7afdee3d8f10.png)



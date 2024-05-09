# Exam 2
Import the dataset Movies_A1. This dataset contains information about movies. Address the following questions:

## Questions 1
Using data on chronic kidney disease patients, test whether if the hemoglobin levels of individuals with chronic kidney disease exceed 10.5. Consider an alpha level of 0.05 and answer the following questions:
- Q1. How many rows and columns do we have?
- Q2. The variable 'gross' represents the gross income of the movies. Calculate the average, the standard deviation, and the five-number summary of the variable 'gross'. The average of the variable 'gross' is (56295319.75), the standard deviation is (28224162.19), and the third quartile is (80513846.0).
- Q3. The variable 'duration' represents the duration of the movies. Plot a scatter plot and calculate the correlation coefficient between the variables 'duration' and 'gross'. Repeat the analysis using the variables 'budget' and 'gross'.
The relationship between 'duration' and 'gross' is (weak), and the correlation coefficient between 'budget' and 'gross' is (0.7518).
- Q4. The variable 'cast_facebook_likes' represents the number of likes on Facebook for the cast of the movies. It is discrete and categorized as follows:
  - 1: Less than 1000 likes.
  -  2: Between 1000 and 5000 likes.
  - 3: Between 5000 and 10000 likes.
  - 4: More than 10000 likes.
Calculate the average 'gross' for movies with cast Facebook likes less than 1000 and for movies with cast Facebook likes more than 10000. The average of the variable 'gross' for movies with cast Facebook likes less than 1000 is (41328769.5), and the average for movies with cast Facebook likes more than 10000 is (88538349.0).
- Q5. The variable 'Metascore' represents the Metascore rating of the movies. Find the correlation coefficient between 'Metascore' and 'gross'. The relationship between 'Metascore' and 'gross' is (weak).
- Q6. The variable 'OscarWon' indicates whether the movie won an Oscar (1) or not (0). Find the largest gross income of movies that won an Oscar and the largest gross income of movies that didn't win an Oscar. The largest gross income of movies that won an Oscar is (102193707), and the largest gross income of movies that didn't win an Oscar is (86365946).
- Q7. The variable ‘oldness’ represents the age of the movies. Create a new column, called 'age_group', and assign values as follows:
  - Assign the letter ‘A’ to movies with oldness less than 10.
  - Assign the letter 'B' to movies with oldness between 10 and 20.
  - Assign the letter 'C' to movies with oldness more than 20.
Calculate the average of the variable 'gross' for each of the previous categories.
The average of the variable 'gross' for the group A is (X Blank 13), the average of the variable 'gross' for the group B is (X Blank 14), and the average of the variable 'gross' for the group C is (X Blank 15) (for all values type a single number rounding up to 4 decimal places).
- Q8 The variable 'duration' represents the duration of the movies. How many unique durations are there in the dataset? What is the maximum duration?
There are (X Blank 16) unique durations in the dataset. The maximum duration is (X Blank 17) (in both cases type a single number).
- Q9 Plot a histogram of the variable 'duration' using 5 bins. Describe the distribution.
The distribution is (right-skewed/pretty symmetric/left-skewed) | X Blank 18) and (unimodal/bimodal/multimodal) (X Blank 19).
- Q10 Sort the data using the variable ‘imdbRating’. What is the index value for the highest rated movie?
The index of the highest rated movie is (X Blank 20) (type a single number).
- Q11 Calculate the percentage of movies with an 'imdbRating' above 7.5. Repeat the analysis for movies with an 'imdbRating' below 5.0.
The percentage of movies with an 'imdbRating' above 7.5 is (X Blank 21), and the percentage of movies with an 'imdbRating' below 5.0 is (X Blank 22) (for both values type a single number rounding up to 4 decimal places).

## Questions 2
- Q1: The number of individuals with chronic kidney disease with normal red blood cells is (write the number, do not use decimals)
- Q2: Using all the data, the lowest value of the hemoglobin levels is (write the number, use two decimals) 
- Q3: Plot the proper chart to answer the following question: the distribution of hemoglobin levels of individuals in this sample is (write: symmetric/right skewed/left skewed) 
- Q4: The correlation coefficient between age and blood glucose random levels is (write the number, use three decimals)
- Q5: Using all the data, construct a 95% confidence interval around the proportion of individuals with hypertension. The lower limit is (write the number, use three decimals) ___ and the upper limit is (write the number, use three decimals) 
- Q6: The proportion of individuals with diabetes mellitus among those with chronic kidney disease is
- Q7: Test if the proportion of individuals with diabetes mellitus among those with chronic kidney disease is less than 40%. (write: it is/it is not) Use alpha = 0.05.
- Q8: Test if the proportion of individuals with diabetes mellitus among those with chronic kidney disease is more than 50%. (write: it is/it is not) Use alpha = 0.01.

- Q9
  -- a) What is the probability that the adjusted gross of a randomly selected movie lies between $66,000,000 and $74,000,000? (type a single number, round up to four decimal places)
  -- b) What is the probability that the Metascore of a randomly selected movie is greater than 75? (type a single number, round up to four decimal places)

  -- c) What is the probability that the duration of a randomly selected movie lies within 0.5 standard deviations of the mean? (type a single number, round up to four decimal places)

  -- d) What is the probability that the IMDb rating of a randomly selected movie is exactly 5.2? (type a single number, round up to four decimal places)

  -- e) What is the adjusted gross corresponding to the bottom 7%? The top 4%? (round up to four decimal places in both cases)

  -- f) What is the z-score of a movie whose IMDb rating is 7.4?
- Q10

  -- a) What is the probability that the next movie will have a duration of exactly 83 minutes? (type a single number. Round up to four decimal places)

  -- b) What is the probability that the next movie will have a Metascore within the next 102 minutes? (type a single number. Round up to four decimal places)

  -- c) What is the probability that the next movie will have an IMDb rating between 4.7 and 5.2 minutes? (type a single number. Round up to four decimal places)

  -- d) What is the probability that the next movie will have an IMDb rating of exactly 7.7? (type a single number. Round up to four decimal places)

  -- e) What is the probability that the next movie will have a budget adjusted to be at least $40,000,000 if the average budget of movies is $60,000,000? (type a single number, round up to four decimal places)

  -- f) What is the probability that the next movie will not have an Oscar nomination for at least 2 years? (type a single number, round up to four decimal places)

## Questions 3
Using the whole sample, create a new variable that divides the individuals between those with high hemoglobin levels (individuals with hemoglobin levels above its average) and those with low hemoglobin levels (individuals with hemoglobin levels below or equal to its average). Then test if the average age is different in these two groups of individuals. Consider an alpha of 0.1 and respond to the following questions:
- Q1: The number of individuals in the group with high hemoglobin levels is (write the number, do not use decimals)
- Q2: The average age in the group with low hemoglobin levels is (write the number, use two decimals) 
- Q3: The standard deviation of age in the group with high hemoglobin levels is (write the number, use two decimals) 
- Q4: The test statistic of the test is (write the number, use two decimals)
- Q5: The p-value of the test is (write the number, use two decimals) 
- Q6: The lower bound of the confidence interval of the difference in means is ___(write the number, use two decimals), and its upper bound is ___(write the number, use two decimals)

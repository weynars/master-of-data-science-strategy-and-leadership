Source: https://www.practicaldatascience.org/html/exercises/Exercise_CommandLine_2_Advanced.html

**Exercise 1. Checking Files**
Count the number of files in the `thursdays_and_fridays` folder.
`ls thursdays_and_fridays | wc -l`

**Exercise 2. Combining files**
Combine all the files in one.
`cd thursdays_and_fridays`
`cat *.csv > thursdays_and_fridays.csv`

**Exercise 3. Viewing your Results**
Check the new file top 5 lines.
`head thursdays_and_fridays.csv`

**Exercise 4. Editing**
Edit `NYC311_column_names.txt` to exclude the square brackets using Nano.
`cd ..`
`nano NYC311_column_names.txt`

**Exercise 5. Cleaning Up**
Delete the `raw data` folder and all its contents.
`rm -r raw\ data`
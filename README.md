>**Note**: Please **fork** the current Udacity repository so that you will have a **remote** repository in **your** Github account. Clone the remote repository to your local machine. Later, as a part of the project "Post your Work on Github", you will push your proposed changes to the remote repository in your Github account.

### Date created
23 November 2022 

### Project Title
Udacity US Bikeshare Data

### Description
In this project, I used Python to explore data related to bike share systems for three major cities in the United States—Chicago, New York City, and Washington. I imported the data and answered interesting questions about it by computing descriptive statistics. I also wrote a script that takes in raw input to create an interactive experience in the terminal to present these statistics.

### User Input - An Interactive Experience

The bikeshare.py file is set up as a script that takes in raw input to create an interactive experience in the terminal that answers questions about the dataset. The experience is interactive because depending on a user's input, the answers to the questions on the previous page will change! There are four questions that will change the answers:

Would you like to see data for Chicago, New York, or Washington?
Would you like to filter the data by month, day, or not at all?
(If they chose month) Which month - January, February, March, April, May, or June?
(If they chose day) Which day - Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, or Sunday?

### The Datasets
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

Start Time (e.g., 2017-01-01 00:07:57)
End Time (e.g., 2017-01-01 00:20:53)
Trip Duration (in seconds - e.g., 776)
Start Station (e.g., Broadway & Barry Ave)
End Station (e.g., Sedgwick St & North Ave)
User Type (Subscriber or Customer)
The Chicago and New York City files also have the following two columns:

Gender
Birth Year

### Data provider
The data is provided by Motivate, a bike share system provider for many major cities in the United States, to uncover bike share usage patterns. You can find out more about the company at www.motivateco.com

### Statistics Computed

#1 Popular times of travel (i.e., occurs most often in the start time)

most common month
most common day of week
most common hour of day

#2 Popular stations and trip

most common start station
most common end station
most common trip from start to end (i.e., most frequent combination of start station and end station)

#3 Trip duration

total travel time
average travel time

#4 User info

counts of each user type
counts of each gender (only available for NYC and Chicago)
earliest, most recent, most common year of birth (only available for NYC and Chicago)

### Files used
bikeshare.py
chicago.csv
new_york_city.csv
washington.csv

### Credits
www.udacity.com


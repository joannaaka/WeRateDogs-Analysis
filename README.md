# WeRateDogs-Analysis: Project Overview 

* Accessed Twitter API and programmatically download files
* Extensive Data Wrangling 
* Generating Insights on Dogs Ratings 

## Description 
WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. The account shares images of the dogs with a brief comment, then let their followers rate the dogs. These ratings almost always have a denominator of 10 with the numerator almost always above 10. For this project, WeRateDogs has downloaded their twitter archive, over 5000+ tweets which we'll be analysing. Also, Udacity ran every image in the WeRateDogs Twitter archive through a neural network that can classify breeds of dogs. Additional data from Twitter API including each tweet's retweet count and favourite(like) count. This project will including Wrangling acts and Analysing of the data.

## Data Wrangling 

### Quality Issues

There are duplicate columns in the data

The data has missing enteries

None is used for null values inplace of standard NaN

Wrong datatype for certain columns

There are wrong values in the Name column

There are enteries for animals or objects that are not dogs

The denominator ratings column have values greater or lesser than 10 and the numerator ratings have value greater than 15

Extract the source name from the source column

### Tidiness Issues

Creating a single column for the dog age that is doggo, floofer, pupper, puppo

Extracting breed and confidence from prediction column

Creating a text number range column from display text range

Extracting weekday from timestamp column.

## Analysis Question 
* How does the characteristics of the dog influence its ratings, retweets counts and favourite counts.These characteristics include breed, age group.

* How does these features of a the tweet affect the engagements on a tweet.These features include Timestamp, Text Range, Source.

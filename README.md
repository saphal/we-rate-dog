
# DATA ANALYST PROJECT.
## WE RATE DOG


### Table of Contents
1. Installation
2. Project Motivation
3. File Descriptions
4. Approach
5. Results
6. Licensing, Authors, and Acknowledgements

<h2>Installation</h2>
I would recommend to use anoconda and jupyter libraries.
Need tweeter API access which can be obtained from filling twitter developer account. Note You may have to wait few weeks due to corona virus.
Link: https://developer.twitter.com/en

<h2>Project Motivation</h2>
This project will be analyzing tweet archive of Twitter user @dog_Rates (A.K.A. WeRateDogs) that rates and comments on people's dogs. Data gather from real world always isn't clean. Python libraries are used to gather, assess and clean its quality/tidyness.

We are interested to answer the following two questions:

1. Famous breed of the dog?
2. Popular dog stage?
3. Is there any correlation between retweet and  favorites?
4. Which gender of dog are more popular ?

File Descriptions
The notebook available here showcases work related to the above questions.

<h2>File Descriptions</h2>

twitter-archive-enhanced-2.csv
WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for you to use in this project. 
URL :https://support.twitter.com/articles/20170160

image-predictions.tsv
image dataframe downloaded from below url.
URL :https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv

tweet_json.txt
holds the dataframe for tweet,fav tweet and so on provided by udacity.

twitter_archive_master.csv
The master data set which we obtained after cleaning the above dataset and merging the date set in to one master copy. The data we used to analyze and visualize.

<h2>Approach</h2>
Both visual and programatic assessments were done to point out quality and tidiness issues. Quality issues are content issues that is inaccurate or redundant. Tidiness issues are the structural issues and unorganized data frames.

## Quality
* Removing retweets
* Changing tweet id as str
* Changing time stamp to date time object
* Sorting issues with name
* Remove rows with no images url
* Display text column in full
* Change missing values in name from None
* Remove extra character after & in twitter archive
* Count number of source
* Change data type of various rows
* Find Dog gender
* finding popular dog breeds


## Tidiness

* All tables should be part of one dataset
* Dog "stage" variable in four columns: doggo, floofer, pupper, puppo

<h2>Licensing, Authors, Acknowledgements</h2>


Must give credit to twitter for giving developer account access to use for this project. I would also like to thank we rate dog for providing data and awesome rating. Lastly I would like to thank udacity for providing me this opportunity for this project

### Author
Saphal Adhikari



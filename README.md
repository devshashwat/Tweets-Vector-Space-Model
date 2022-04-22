# TweetsVSM

Using Vector Space Model in Simple Tweets Database using Custom Test Cases.


Below are the steps to successfully run the sample project in your system:

•	Open the VSMTweets Folder > src > TweetsVSM.java

•	External Libraries folder contains add two jar files common-lang3.jar and opencsv-5.6.jar

•	TweetsVSM also contains stopwords.txt and TweetSample.csv files in src folder.

•	Before running, add two jar files common-lang3.jar and opencsv-5.6.jar to Files > Project Structures > Dependencies. ( For adding dependencies in JGrasp, Settings > Path/ClassPath > Workspace > ClassPath > add two jar files path individually from external libraries folder. )

•	These are the external libraries used to read csv files in java.

•	I have used a sample Tweets data here containing 1000 rows. 

•	When you Run and debugging keep the Tweets and stop words file in same folder as this TweetsVSM.java file.

•	All the input for Tweets and stop words have functions but are called in the main function.

•	All the Test Cases have functions which are called in main function with test values.

•	This program gives VSM tf idf, and Search Query Test Cases for ranked search as output.

•	This program gives finds similarity of the phrase search query using cosine similarity.

•	The Ranked output has been sorted in descending order so that we can know which tweet is the most like the test cases we have in the input.

•	There a plenty more test cases which can be used to detect the vaccine misinformation spreading users and if they are verified profiles.

•	I have added the screenshot of test cases and GUI in the folder Test Cases.

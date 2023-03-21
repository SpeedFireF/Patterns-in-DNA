# Patterns-in-DNA
## Short description:
Analysis of the positions of palindromes of cytomegalovirus in the DNA strand to optimize the start of the study of the potential site of the origin of replication

# Contents
[1) The main goal of the study](#the-main-goal-of-the-study)\
[2) Brief information about the data](#brief-information-about-the-data)\
[3) What test to use?](#what-test-to-use?)\
[4) Steps to achieve the goal](#steps-to-achieve-the-goal)\
[5) Results](#results)


### The main goal of the study 
The main goal of the study is to optimize and reduce the cost and time of the study of the origin of replication in cytomegalovirus. Polyndromes in the DNA of the virus help us look for the beginning. Cytomegalovirus is a herpes family, which is why it is believed that it behaves the same way. Based on previous studies of herpes viruses, we can say for sure that polyndromes often indicate the proximity of the origin of replication.
### Brief information about the data
We are given one .txt file, each line of which is an integer from 0 to 228953 - the number of the beginning of a palindrome long from 10 to 18 in the DNA chain (this palindrome size is due to the fact that shorter palindromes are very common and usually do not indicate and do not help in finding the origin of viral replication)
### What test to use?
When examining a date, we must make sure that it is not a random uniform scatter, which means we must use a special statistics test to determine if our date differs from a random one. The best fit for the task criteria is the Chi-Squared Test, which we use in the process
### Steps to achieve the goal
1. Compare with random scatter plot
2. Examine spacing between consecutive palindromes
3. Counts a number of palindromes in nonoverlaping regions fixed size. Try with different sizes
4. Perform a Chi-Squared Test and reject or do not reject the null hypothesis
5. Identify the biggest cluster
### Results
With the whole proccess you can get acquainted in the pdf file, and with the code that was written for output in jupyter notebook

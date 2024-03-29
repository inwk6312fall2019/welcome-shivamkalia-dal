# Inwk6312- Fall 2019 - Final Open Book 

# Programming Task 

Welcome to your final programming quiz

  - You have to clone this repo to your account, you should be seeing this on your account, if someone elses name is listed call an instructor for help.
  - Use the Ubuntu VM / Your PC / Or Python anywhere to write the program.
  - Ensure that you have logged out others from github classroom and github website and you are the only person logged in.
  - Use git add, commit and push to send the code back. 
  - Don't forget to add user name and email on git. 
  - You are allowed to use any form of searching and documentation reading and book reading is promoted
  - Each task is to be saved as a individual python file with the name task0A.py, where A is the sub-tasknumber and 0 is the tasknumber.
  - You cannot talk to your other people or ask for help!
  - You cannon upload your answers through Github webinterface or "forget" to create commits - You will not be evaluated. 

 
# Task 0 - Fizz Buzz

### Objectives
- Create your own empty repository in your github account called fizzbuzz (Public)
- Create a local repository on your computer called fizzbuzz-yourname and set the github repository as remote 
- Write a python program to solve the problem given below
- Add, Commit and Push the code
- In your openbook final repository(the one you cloned from github-classroom) create a file called task0.link and paste the https link to clone your fizzbuzz github repo.  

### Problem 
 "Write a program that prints the numbers from 1 to 100. But for multiples of three print “Fizz” instead of the number and for the multiples of five print “Buzz”. For numbers which are multiples of both three and five print “FizzBuzz”."
 
 ### Note:
 You only need to provide a file with a link to your repository.  YOU SHOULD NOT WRITE THE PROGRAM IN THIS REPO.
 
# Task 1 - Trail

## Halifax Open Data

You are given a csv file(Trail.csv) from [Halifax's open data](https://www.halifax.ca/home/open-data). 

  - The file is a csv (comma seperated values); i.e, it's like a excel spreadsheet but simple
  - You can read the file without modification to it.
  - You are asked to extract some information from it. 

### Trail Data

The CSV you are given has details of the single line representation of trails, that are either owned, maintained, or of interest to HRM.

This is the original source  ->https://catalogue-hrm.opendata.arcgis.com/datasets/1303ee427f7941768e56e31ef74db313_0
And the Data is here:->  https://catalogue-hrm.opendata.arcgis.com/datasets/1303ee427f7941768e56e31ef74db313_0/data

### Objectives

Write the code under task1.py: 
Use functions to:

1. Classify the Data into diffrent lists for each type of "General Condition" that you find in the data set. [ Ex: Some Trails are good, some are poor or unknown.We need a list of trails that are good and poor and so on.. ]

2. Find the number of trails that are installed after the year 2000. Return a list of them. [use "Installation Year for this"]

3. How many trails are currently Active? [Use "Status" to find this] How many have lighting? [Use "Lighting" to do this]. How many are both "Walking" and have "Biking"? 

4. Return a tuple containing the following (Trail Name, General Condition, Lighting, Status, Hiking, Biking, ATV) for trails that can be hiked and biked 


# Task 2 - l33t copy 

### Objectives

Write the solution in task2.py
You are to create a program that does text file copying. But with a twist!

    - You get a target file name and (optionally a target folder) 
    - Copy specific pages of text to a new file (Assume 25 lines to be a page of a text)
    - Copy with l33t code on (Write a function for this!)
    - Create a menu to provide these options and get all the input from the users
    
Also, when done copying display a report indicating success and the count of pages, line and words copied and the count of alphabetic characters and also a count of numeric characters written. 
Please ensure that the code handles errors in user input or system faluts. [Handle exceptions]

### l33t code rules

    - Replace o or O with 0(number) and a or A with 4
    - Replace e or E with 3 and i or I with 1
    - Words ending with (suffix) "-er" ends with "-xor" or "-zor" [ hacker -> h4x0r) 

# Task 3 - Book play

### Objectives

The books are Book1.txt, Book2.txt, Book3.txt they are found in your repo. You also have, a file called 20k.txt that contains a list of common english words. Using this you can find the characters and nouns in the books. 
Open the book in python and write the following functions to perform the following operations on each of the book. Pass the book as a argument to the functions and return the requested data structure / type.
  
1. Function name: unique_words - Returns: A list containing only one copy of the words. (for example, if the word "it" appears 50 times in the book, there should be only one "it" in the tuple)
2. Function name: count_the_article - Returns: An Integer that counts the total number of words that are in the list. => ["a", "the", "at", "run", "to","and","are","or","for","an","this"]
3. Function name: character_word_count - Returns: A Dicionary containing words in the book as key and the character count as the values. 
4. Function name: starts_with_vow - Returns: An Integer In each book count the total number of words that start with this following collection tuple =>  ("a", "e", "i", "o", "u").
5 Function name: rare_words - Returns: A list of words in Books that are non present in 20k.txt [Do it for each book]
6 Function name: unused_word - Returns: A list of words in the 20k.txt that are non present in any Books and the count. 


# Task 4 - APIC-EM API
You are given a code to talk to the APIC-EM sandbox controller in the files, create-ticket.py and get-network-hosts.py through RESI. 
The API-DOCS can be found at https://developer.cisco.com/site/apic-em/docs/api.gsp

### Objectives
[Create a newfile called task03.py and import create-ticket.py to achive this]

1. Modify get-network-host.py to display return a dict that contains the hosts with their Names and IP Addresses tuple as keys and MAC Addresses as values. [This should be done on the same file]

2. Write a new function called getnetworkdevicecount that gets the count of network devices. (The API can be found under Inventory -> network-device -> count)


Use the controller at: https://sandboxapic.cisco.com/

### Max time: 3 hours!

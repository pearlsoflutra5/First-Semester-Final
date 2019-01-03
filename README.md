# First-Semester-Final

## Synopsis
This is a very basic program that allows extra practice with concepts learned specifically in school. It is a code that can be concentrated to any curriculum with small adjustments and additions. 

## Code Example
The general outline of code makes you choose a class (ex: english), a topic (ex: vocab), and for this specific example a book (ex: the old man and the sea), then it will generally ask if you want to do random (English, history, Chemistry) for these specific classes mentioned it will take an array with the information stored in it and will output the questions. For math, it will give the instructions for the concept of adding arrays and it will ask if you want to do the outlined or create your own. 

``` 
if(list.equalsIgnoreCase("The Old Man and the Sea") ){
  System.out.print("Do you want to do random: ");
	String random = input.nextLine();
	if (random.equalsIgnoreCase("no")){
	  String [][] book = theOldManAndTheSeaVocab();
		knowSecondColumn(book, "word", "");
		System.out.print("\nWhat next: ");
		subTopicEnglish();
	}  
  
```
This exerpt is a piece of code if you have chosen to do english, vocab, The Old Man and the Sea, and no (for random). It will read the array that has all of the data for the vocab list The Old Man and the Sea and apply it to the String array book. It will then pass book, as well as a key word for the question, as parameters for the method knowSecondColumn which will then give the questions and check to see if it is correct. It will then give you an answer of how many was correct out of the total list and will then output the statement what next before calling subTopicEnglish which will then act as if you typed english in the beginning. 

## Installation
This program is very easy to access I have added a the direct code to reach really quickly with the name of FinalCode.java. with the cloning of this project, there should not have to be any other installations.  

## Motivation
I have taken several classes and I needed more focused practice. I needed to practice specific questions with specific answers that the teacher required. I decided to create my own practice. I also know that I wanted to

## Contributors
I want this code to be available to everyone who wants to adapt it for their own purposes as long as the original code stays the same. 


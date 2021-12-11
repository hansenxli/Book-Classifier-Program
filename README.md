# Book Classifier Program

## Author: Hansen Li

This is a program written by Hansen Li in Java for the AT&T Technology Development Program's technical assessment. This program takes in a text file of book information at runtime in the terminal and displays details about the oldest book of the author who has published the most books input.  
As this is a Java program, it is necessary to have Java installed.

## Files (3)
Main.java
BookList.java
Book.java

## Compiling
To compile, run the following line in your terminal:
	javac Main.java BookList.java Book.java

## Executing
To execute, run the following line in your terminal:
	java Main.java *bookdata.txt*

Include a text file in the same source folder as the program files when executing.

## Text File Details
Each line of the text file should contain a book's title (stripped of punctuation), its date of publication, its author, and its length in page numbers.
These fields should be delimited with commas with details of one book per line.
The author may only be one of the following:
	Steven King
	Rudyard Kipling
	Isaac Asimov
	Suzanne Collins
	
Note that the mispelling of Stephen King's name is intentional for the purposes of this program.

Example lines for the text file:
	Carrie,06/13/1982,Steven King,762
	Kim,02/03/1910,Rudyard Kipling,526

Two example text files have been included (using the text from the instructions of this assignment).

Please email [Hansen Li](mailto:hansenxli@gmail.com) for any questions

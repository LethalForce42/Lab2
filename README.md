# Lab2

This program basically reads a csv file from SpotifyCharts and then creates
an output file containing all the artists and how many times they appear on
the list. The program scans in the input file and then create a 2d array with rows and 
columns. There are multiple try/catch methods used to catch possible exceptions
and throw/block them while displaying the appropriate message if necessary.
To print the needed information to an output file, a PrintWriter is used to
write to a text file. The information that is written in the file is generated
by using a for loop to call the artists array until the array has reached the end.
The output file thus contains each artists name that appears on the csv file and 
how many times they appear on the list while making sure that an artist who 
appears multiple times is not given a separate line of text.

***You need to run the Lab2.java file which is located in the src folder. Make sure
when you clone repository that the SpotifyCharts csv file is located in the Lab 2 
folder so that the code can read it without throwing a Nullpointer error.***

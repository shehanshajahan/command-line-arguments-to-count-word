# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific location of interest
### Step 2: 
In the same location as the text file, create a python program
### Step 3: 
In python program, import sys and open a text file with argument 'sys.argv[1]'
### Step 4:  
Using read() and split(), split the lines in the file into a sequence of words
### Step 5: 
Using len() count the number of words in the text file
### Step 6: 
In command prompt, initiate python followed by program name and text file name to get the output
## PROGRAM:
```
#Program to find the word count using command line arguments
#Developed by: Shehan Shajahan
#Register Number: 23008724
fname=input("Enter the file name: ")
num_words=0
with open(fname,'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print("Number of words: ",num_words)
```
### OUTPUT:
![Screenshot 2024-01-02 172107](https://github.com/shehanshajahan/command-line-arguments-to-count-word/assets/139317389/d3d37ee7-4c81-473f-9eb7-52e149b305da)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.

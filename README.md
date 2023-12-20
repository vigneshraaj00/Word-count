# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for getting the word count from a text file 
### Step 2: 
 Open the required file by using the function "with".
### Step 3: 
Then use the laptop to assign the i value in the file.
### Step 4:  
Using split function to spilt the words
### Step 5: 
Finding the given length of the words by using len() fuction.
### Step 6: 
Calling the function and Printing the number of words.
## PROGRAM:
```
#Program to find the word count.
#Developed by: TAMILARASAN K S.
#RegisterNumber:23000080



num_word=0
with open ("sample.txt",'r') as f:
for i in f:
word=i.split()
num_word+=len(word)
print("number of words ={}".format(num_word)
```
### OUTPUT:
![image](https://github.com/Lokhnath10/Word-count/assets/138969918/3efe7e6f-36c1-4fc5-9b6a-b7b0d5c54710)

![image](https://github.com/Lokhnath10/Word-count/assets/138969918/ba7d8abd-2126-439f-a8c9-8898bf93a956)



## RESULT:
Thus the program is written to find the word count from a text.

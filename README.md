# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file and add some content into it
### Step 2: 
Open file using with keyword/built-in function in read mode.
### Step 3: 
Use read() to read the contents of the file
### Step 4:  
Split the lines using split().
### Step 5: 
Iterate the list and increment the count
### Step 6: 
print the output.
## PROGRAM:
def wordcount():
    count=0
    with open("file.txt","r") as f2:
        data=f2.read()
        for line in data.split():
            count+=1
    print("The total number of word count is",count)
wordcount()
### INPUT:
![Screenshot from 2023-01-25 23-52-43](https://user-images.githubusercontent.com/121412904/214799393-fd760dee-eb09-4a02-b074-ba219e40da22.png)


### OUTPUT:
![Screenshot from 2023-01-25 23-52-06](https://user-images.githubusercontent.com/121412904/214799489-0345408e-393f-4573-afa5-d67d7a4d8ccb.png)

## RESULT:
Thus the program is written to find the word count from a text.

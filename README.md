# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:create a file with .txt file extension

### Step 2: add some text in that file
 
### Step 3: create a python file

### Step 4: write a code to count the number of words in that file

### Step 5: run the program

### Step 6: display the output

## PROGRAM:
```
def program():
    count=0
    with open("text.txt","r") as f:
        for data in f:
            word=data.split()
            for word in words:
                count+=1
    print("Ttotal number of words:",count)
program()



```
### OUTPUT:

![Screenshot 2023-12-26 155020](https://github.com/prasannavenkat01/Word-count/assets/150702500/d13ab23c-719c-4123-b20a-8fca91f6fb08)


## RESULT:
Thus the program is written to find the word count from a text.

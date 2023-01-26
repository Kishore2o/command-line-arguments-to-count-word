# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys

### Step 2:
Then decleare count is equal to 0 
 
### Step 3: 
read the file with python file name 

### Step 4:  
Splitting the word 

### Step 5: 
After splitting count the number of words in the line 

### Step 6: 

In last statement give the print statement

## PROGRAM:
```
Developed by : S.Kishore
Register no : 22008388
import sys,
count=0
with openm(sys.argv[1],'r) as f:
    for line in f:
    word=line.split()
    count+=line.(word)
print("Word Count in File=",count)

```

### OUTPUT:
![image](https://user-images.githubusercontent.com/118679883/214784363-04a40164-ee7f-4d81-8e4a-69c6852c6c70.png)

![image](https://user-images.githubusercontent.com/118679883/214784446-0a60bce7-d70e-4a46-adde-1df830bf311a.png)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.

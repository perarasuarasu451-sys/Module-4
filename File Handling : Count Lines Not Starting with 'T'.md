# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```

file=open("story.txt","r") 
count=0 
for lines in file: 
   if lines [0] not in 'T': 
      count+=1 
print(count)
```
## Output
<img width="361" height="71" alt="438931030-d4b93207-2ea7-4b97-8047-17da8d4ce0e0" src="https://github.com/user-attachments/assets/d5e19636-ee1c-4613-9a58-1d54776c074d" />

## Result
Thus the program executed successfully.

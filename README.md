Module-1 Day-1 SEB 
AIM:

To write a Python program that accepts a character as input and checks whether it is a vowel or not using character literals.

ALGORITHM:

#STEP 1:

Start the program.

#STEP 2:

Accept a single character input from the user.

#STEP 4:

Check whether the entered character is one of the vowels — 'a', 'e', 'i', 'o', 'u' or their uppercase forms 'A', 'E', 'I', 'O', 'U'.
#STEP 5:

If it matches, print that the entered character is a vowel.

#STEP 6:

Otherwise, print that it is not a vowel.
#STEP 7:

Stop the program.

PROGRAM:
```

ch = input("Enter a character: ")   # get character input
if ch in ('a', 'e', 'i', 'o', 'u', 'A', 'E', 'I', 'O', 'U'):
    print(ch, "is a vowel.")
else:
    print(ch, "is not a vowel.")
```

OUTPUT:
<img width="366" height="141" alt="Screenshot 2025-10-18 191907" src="https://github.com/user-attachments/assets/2973f791-4fb4-4d50-a33c-fb1633a598ab" />



RESULT:
The program successfully accepts a single character from the user and identifies whether it is a vowel or not using character literals in Python.

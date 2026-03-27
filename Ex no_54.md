## print all the letters of the English alphabet.

SAMPLE OUTPUT : CAPS and add space to each alphabet

A B C D E F G H I J K L M N O P Q R S T U V W X Y Z

# AIM:
To write a C program to print all the letters of the English alphabet.

# Algorithm:
Start Initialize a character variable ch with 'A'. Loop from 'A' to 'Z': Print the character. Print a space after each character. End the loop once 'Z' is printed. End

# Program:
#include <stdio.h>

int main() { char ch;

for (ch = 'A'; ch <= 'Z'; ch++) {
    printf("%c ", ch);
}

return 0;
}

# Output:

<img width="567" height="153" alt="image" src="https://github.com/user-attachments/assets/f08ef73f-ff86-4efa-a49e-1040213f8e65" />

# Result:
Thus the program was executed and the output was verified successfully.

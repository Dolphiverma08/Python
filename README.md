# Python
Programming in Python
Write python program to print first letter of your name 
a) Example: Peter
               *      *
               *             *
               *              *
               *      *
               *
               *
               *
b) Print your name by using for loop

c) check the user name is palindrome or not
star_pattern = [
    "***** ",
    "*    *",
    "*    *",
    "*    *",
    "***** "
]
for pattern in star_pattern:
    print(pattern)

name = 'Dolphi'
print("\nPrinting each letter of the name:")
for letter in name:
    print(letter)

is_palindrome = name.lower() == name[::-1].lower()
print('\nName is a palindrome' if is_palindrome else 'Name is not a palindrome')


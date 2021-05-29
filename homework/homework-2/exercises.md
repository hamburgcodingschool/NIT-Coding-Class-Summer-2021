# Homework
- [Exercise 1](#exercise-1)
- [Exercise 2](#exercise-2)
- [Exercise 3](#exercise-3)
- [Exercise 4](#exercise-4)
- [Exercise 5](#exercise-5)
- [Exercise 6](#exercise-6)
- [Exercise 7](#exercise-7)
- [Exercise 8](#exercise-8)
- [Exercise 9](#exercise-9)
- [Exercise 10](#exercise-10)
- [Exercise 11](#exercise-11)
- [Exercise 12](#exercise-12)
- [Exercise 13](#exercise-13)
- [Exercise 14](#exercise-14)
- [Exercise 15](#exercise-15)

## Exercise 1
### Input and output
Write a program that ask the user for his name and prints a greeting.
```
Please enter your name:

Hello <NAME>, welcome to the Learn to Code course.
```

> **Hint:**<br />
> Use `prompt()` for the input and `document.write()` for the output .


## Exercise 2
### Format text
Choose a simple Ascii art from the website https://www.asciiart.eu/.<br />
Output it to the ___console___.
```
￼        _______
       //  ||\ \
 _____//___||_\ \___
 )  _          _    \
 |_/ \________/ \___|
___\_/________\_/______
```

> **Bonus goal:**<br />
> Can you do the same using `document.write()` to output to HTML instead?


## Exercise 3
### Currency converter
Write a program that asks the user for an amount in USD.<br />
Output that amount converted to EURO.

> **Bonus goal:**<br />
> Use a precision of 2 decimal points: `3.45€`.


## Exercise 4
### Sum loop
Write a program that asks the user for a number `n` and prints the sum of the numbers `1` to `n`.

> **Example:**<br />
> User inputs `5`<br />
> Output:<br />
> `1 + 2 + 3 + 4 + 5 = 15`


## Exercise 5
Modify the Exercise 4 so that only multiples of three or five are considered in the sum.

> **Example:**<br />
> User inputs `17`<br />
> Output:<br />
> `3 + 5 + 6 + 9 + 10 + 12 + 15 = 60`


## Exercise 6
Modify Exercise 4 so that the program asks the user for a number `n` and gives them the possibility to choose between computing the sum or computing the product of 1 to n.


## Exercise 7
Write a program that check wether a number exists inside an array of numbers.
```
let n = 5;
let numbers = [4, 7, 10, 12, 1, 8, 20];
// for this case the result would be false
```


## Exercise 8
Write a program that prints **1 per line** only the names on odd positions in an array of names.
```
let names = [“Josie”, “Cathrin”, “Bob”, “Max”, “Hannah”, “Alex”];
```


## Exercise 9
Write a program that prints the name with more characters in an array of names.


## Exercise 10
Write a program that asks the user for a name and outputs that name backwards.


## Exercise 11
Write a program that asks the user for a sentence and outputs the words in the ___console___, one per line, in a rectangular frame. For example the sentence "Hello World in a frame" gets printed as:

```
*********
* Hello *
* World *
* in    *
* a     *
* frame *
*********
```
> **Hint:**<br />
> Research how to `split()` Strings.


## Exercise 12
### Triangles
Write a programa that asks the user for a size `s` and then outputs a triangle with the height and width of `s`

> **Example:**<br />
> User inputs `4`<br />
> Output:
```
*
**
***
****
```
> **Bonus goal:**<br />
> Also ask the user for how many triangles to print.<br />
> User inputs size `3`<br />
> User inputs times`2`<br />
> Output:
```
*
**
***
*
**
***
```


## Exercise 13
### Xmas tree 🎄

Write a programa that asks the user for a height `h` and then output a Xmas Tree with an height of `h`.
> **Example:**<br />
> User inputs `5`<br />
> Output:
```
    *
   ***
  *****
 *******
*********
    I
```
> **Hint:**<br />
> Don't forget the stem.


## Exercise 14

List a table that multiplies all the numbers from 1 to 10.<br />
Format your output to something like this:
```
 1   2   3   4   5   6   7   8   9  10
 2   4   6   8  10  12  14  16  18  20
 3   6   9  12  15  18  21  24  27  30
 4   8  12  16  20  24  28  32  36  40
 5  10  15  20  25  30  35  40  45  50
 6  12  18  24  30  36  42  48  54  60
 7  14  21  28  35  42  49  56  63  70
 8  16  24  32  40  48  56  64  72  80
 9  18  27  36  45  54  63  72  81  90
10  20  30  40  50  60  70  80  90 100
```

## Exercise 15
### Guessing Game

Write a guessing game where the user has to guess a secret number between 1 and 100 generated randomly by the program.
After every guess the program tells the user whether their number was too large or too small.<br />
After 6 tries the game is over and the user loses.

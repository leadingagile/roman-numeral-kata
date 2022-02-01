# Roman Numeral Calculator Kata

The Romans wrote numbers using letters : I, V, X, L, C, D, M. (notice these letters have lots of straight lines and are hence easy to hack into stone tablets). In this simple kata, your task is to create a converter which takes a number and returns it's Roman Numeral representation.

## Features

### Convert from Number to Roman Numeral

#### Convert Valid Number
Given an input of an integer between 1 and 3,999, return the Roman Numeral equivalent.

Example:

| Input | Output    |
|:-----:|:---------:|
| 1     | I         |
| 349   | CCCXLIX   |
| 3999  | MMMCMXCIX |

#### Invalid Number
Given an invalid number as the input, output `Invalid Number: Roman Numerals are between 1 and 3,999`

### Convert from Roman Numeral to Number

#### Convert Valid Roman Numeral
Given an imput of a Roman Numeral between I and MMMCMXCIX, return the numerical equivalent

Example:

| Input     | Output |
|:---------:|:------:|
| I         | 1      |
| CCCXLIX   | 349    |
| MMMCMXCIX | 3999   |

#### Invalid Roman Numeral
Given an input of invalid characters for the Roman Numeral, output `Invalid Roman Numeral: Valid characters are I, V, X, L, C, D, M`

## Roman Numeral Rules

- Roman numerals consist of the following letters: I, V, X, L, C, D, and M

<div style="margin-left: 4em">

| Number | Roman Numeral |
|:------:|:--------:|
| 1 | I |
| 5 | V |
| 10 | X |
| 50 | L |
| 100 | C |
| 500 | D |
| 1000 | M |

</div>

- If a lesser numeral is put before a bigger it means subtraction of the lesser from the bigger ("IV" means four, "CM" means nine hundred)
- If the numeral is I, X or C you can't have more than three
- If the numeral is V, L or D you can't have more than one

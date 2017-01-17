# Roman Numerals

The Romans wrote their numbers using letters; 
specifically the letters 
* 'I' meaning '1' 
* 'V' meaning '5' 
* 'X' meaning '10' 
* 'L' meaning '50' 
* 'C' meaning '100' 
* 'D' meaning '500' 
* 'M' meaning '1000'

There were certain rules that the numerals followed which should be observed:

* The symbols 'I', 'X', 'C', and 'M' can be repeated at most 3 times in a row. 
* The symbols 'V', 'L', and 'D' can never be repeated. 
* The '1' symbols ('I', 'X', and 'C') can only be subtracted from the 2 next highest values ('IV' and 'IX', 'XL' and 'XC', 'CD' and 'CM'). 
* Only one subtraction can be made per numeral ('XC' is allowed, 'XXC' is not). 
* The '5' symbols ('V', 'L', and 'D') can never be subtracted.

# Examples

| Roman Numeral | Value |
| I| 1 |
|IV| 4 |
|V| 5 |
| VI| 6|
| X| 10|
| L|50|
|C|100|
| D|500|
|M|1000|
|MCMXLIV|1944|
|MCMXCIV|1994|
|MMVI|2006|

# Kata

Implement the
`public int convert(String value)`
method in RomanNumeralConverter.java

There is a test case RomanNumeralConverterTest.java which you may want to use.

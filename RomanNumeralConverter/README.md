# Roman Numberal Converter
The Roman Numberal Converter tests more advanced logic skills

## Background
The Roman Numeral system is a base 10 numeral system using letters instead of numbers like I, V, X, L, C, D, and M with each letter representing a 1 or a 5 multiplied by a power of 10. The table below outlines each Roman Numeral letter and their Arabic Numeral equivalent:

| Roman Numeral | Arabic Numeral |
| --- | --- |
| "I" | 1 |
| "V" | 5 |
| "X" | 10 |
| "L" | 50 |
| "C" | 100 |
| "D" | 500 |
| "M" | 1000 |

To count up in Roman Numerals, count as high as you can by repeating the 1's number until you can reach a 5's number. Then represent that number with the 1's number before the 5's number. For example, counting to 10 in Arabic numerals is `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, and the Roman Numeral equivalent would be `I`, `II`, `III`, `IV`, `V`, `VI`, `VII`, `VIII`, `IX`, `X`. By the same token, 20 is `XX` and 30 is `XXX` but 40 is `XL`.

**Note:** For the purpose of this assignment, you only need to support numbers up to 3,999 (`MMMCMXCIX`)

If there are any errors in the input, report them before doing any calcluations and properly give an error message.

## Details
In any language you want (including pseudo-code), write a program, function, method, or class that takes an string parameter that represents a Roman Numeral (i.e. "IV", "XI", "LXII") and converts it to its Arabic Numeral integer equivalent. Some example conversions would be:

| Roman Numeral | Arabic Numeral |
| --- | --- |
| "IV" | 4 |
| "XI" | 11 |
| "LXII" | 62 |
| "MMMCMXCIX" | 3999 |
| "CDLXXVIII" | 478 |
| "VX" | `ERROR` |
| "IIII" | `ERROR` |
| "VV" | `ERROR` |

**Note:** The last 3 entries say `ERROR` because they are not valid Roman Numerals.

## Acceptance Criteria

Your Program must run through all 8 examples in the `Details` table and return the Arabic Numeral equivalent or raise an error if it is an invalid Roman Numeral. If you are using pseudo code, then talk through each of the 8 examples and how your program would handle the input and output.

## Hints

 - Don't worry about error checking at first. Just work through the sunny day cases before trying any rainy day cases
 - Be sure to read through all of the instructions.
 - If you're stuck, feel free to ask for help. That's what a team is for :)

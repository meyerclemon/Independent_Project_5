# Word Counter

#### A program to tell you how many times an inputted word is contained within an inputted sentence. 4/26/2019

#### By **Maya Frame**

## Description
A program created with C# where a user can input a word and determine how many times it appears within an inputted sentence.

### Example
| Spec | Input |
| :-------------     | :------------- |
| **User Word Input** | "Boy" |  
| **User Sentence Input** | "Oh boyo boy! Can you believe they boycotted Boy George for not looking boyish?" |
| **Expected Output** | "2 matches" |

### Specs
| Spec | Word Input| Sentence Input |Output|
| :-------------     | :------------- | :------------- |:------------- |
| User inputs word string and program recognizes string has been entered| "word"| |  "word"|
| User inputs sentence string and program recognizes string has been entered|| "Oh my word |  "Oh my word" | 
| Program changes all input to lower case. |  "Word" | "More words"| "word" / "more words"| 
| Program splits sentence into an array| "boy" |  "Oh boy oh boy" |  "'oh','boy','oh','boy'" | 
| Program loops over the sentence array checking for user input word matches| "boy"| SPLIT: "'oh','boy','oh','boy'"| "2 matches"|
| Program returns only full word matches, excluding longer words that contain matching word string characters.| "boy" | "Oh boyo boy! Can you believe they boycotted Boy George for not looking boyish?" | "2 matches" |

## Setup/Installation Requirements

1. To run this program, you must have a C# compiler.
2. Clone Github repository.
3. Run via Git Bash or other terminal.
4. https://github.com/meyerclemon/Independent_Project_5

## Known Bugs
* No known bugs at this time.

## Technologies Used
* C#

## Support and contact details

_Email mayacframe@gmail.com with any questions, comments, or concerns._

### License

*{This software is licensed under the MIT license}*

Copyright (c) 2019 **_{Maya Frame}_**

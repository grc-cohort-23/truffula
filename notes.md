# Truffula Notes
As part of Wave 0, please fill out notes for each of the below files. They are in the order I recommend you go through them. A few bullet points for each file is enough. You don't need to have a perfect understanding of everything, but you should work to gain an idea of how the project is structured and what you'll need to implement. Note that there are programming techniques used here that we have not covered in class! You will need to do some light research around things like enums and and `java.io.File`.

PLEASE MAKE FREQUENT COMMITS AS YOU FILL OUT THIS FILE.

## App.java
- where main at and explain what the code will be doing
- A starter file for my project where my code/program? will display some flags:
    -h , -nc , path
## ConsoleColor.java
- Where color for our output/program stored as code and enum
- We can print those colored text in the terminal.
- It is like a color libabry books as private?

## ColorPrinter.java / ColorPrinterTest.java
- Where you print text in different colors using the consoleColor library 
- A Unit Test for colorPrinter correctly prints then reset? the terminal color afterward.
## TruffulaOptions.java / TruffulaOptionsTest.java
- A file where it will read the command line then decide which options the user selected and then verify
- A unit test for TruffulaOptions if it actually read the command correctly and follow throughly
## TruffulaPrinter.java / TruffulaPrinterTest.java
- Where we print the folder tree.
- taking over from truffula.options -> continue and do the printing
## AlphabeticalFileSorter.java
- Help clean up, sort files and folders alphabetically before truffulaPrinter work.
# ANTLR-Projects
Language Recognision and translation projects using ANTLR4
This is an Application that can be used to convert CSV input into a JSON input. The Project makes used of ANTLR4 Jar and is written in Java.
The initial step of developing a new language or interpreting a langauge is by creating what we call, a grammar file. A grammar file consists
of a set of rules that define the syntax for the language. The CSV.g4 file provided has all the rules for a CSV file defined in it.
The rules specify what eaach row is composed of, and distincts itsef from a header row.

The Application code is written in Java. The LoadCSV.java file scans and adds all the row field values into the list of hash maps.
The file Translate.java has the main() which takes the input from the console and passes the input throough a scanner, generates tokens
and parse tree and finally walks the parse tree.

On running the application, the CSV input provided in the console is converted to JSON format.


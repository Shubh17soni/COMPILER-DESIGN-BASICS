# COMPILER-DESIGN-BASICS

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : SHUBH SONI

*INTERN ID* : CT06DH414

*DOMAIN* : C PROGRAMMING INTERN

*DURATION* :6 WEEKS

*MENTOR* : NEELA SANTOSH

DESCRIPTION :The objective of this task was to implement a basic lexical analyzer using the C programming language. Lexical analysis is the first phase of the compilation process, and it involves scanning the source code to break it into meaningful units called tokens. These tokens help in identifying the roles of different elements in the code, such as keywords, operators, and identifiers.

In this task, the C program was designed to read a text file containing a series of programming-related words, symbols, and expressions. The purpose was to analyze each word and categorize it correctly as a keyword, operator, or identifier. You sent To achieve this, I used predefined arrays:

One array holds a list of keywords such as "int", "float", "char", "if", "else", "while", "for", and "return".

Another array stores the operators: '+', '-', '*', and '/'.

The program reads the file word by word using fscanf() and checks each word against the keyword array using strcmp() in a loop. If the word matches any of the elements in the keyword array, it is classified as a keyword and printed accordingly.

If the word is not a keyword, the next check is for operators. Here, the program compares the first character of the word with each operator symbol using a loop. If a match is found, the word is classified and printed as an operator. You sent Finally, if the word is neither a keyword nor an operator, the program checks whether the word can be classified as a valid identifier. In C, an identifier must start with a letter (a-z, A-Z) or an underscore (_), and this condition was checked using isalpha() or a direct check for the underscore. If this condition was satisfied, the word was printed as an identifier.

Additionally, the code includes proper error handling for file input, and messages are printed if the file cannot be opened. The output clearly displays the categorization of each word, allowing for easy verification and understanding of how lexical analyzers work at a basic level.

This task not only helped me grasp the core concept of lexical analysis, but also strengthened my understanding of file handling, string operations, and conditional logic in C. It gave me a practical look into how compilers begin the process of translating source code into machine code, starting from recognizing the building blocks of a program.

Moreover, I encountered and resolved some logical and syntax-based issues during implementation—such as fixing errors related to the use of assignment operators in conditionals, and simplifying the logic for identifier detection. This process refined my debugging and problem-solving skills.

Overall, the task served as a hands-on introduction to how a compiler’s frontend works and laid the groundwork for more advanced topics such as syntax parsing and semantic analysis.

*OUTPUT*

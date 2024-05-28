# hamon_bash
# Automated Readability Index
### Shell script to find the suitable grade of a student to read a book.
__./ari.sh__ to run the file
Script takes the filename after run.
To find the automated readability index, there are some aritmetic operations to be executed.No of words, No of Sentences,and No of Characters in the string/file are the parameters for the ARI equation. To find the No of Characters, this script using normal __WC -m__ command. For the no of words __WC -w__ used. For the count of sentence script trying to count the number of occurance of __.?!__ in the given file/string. for this purpose script using __grep -o '[.!?]'__ commnds. Here -o looking for what is specified. to print the number of sentences script adding __-l__ using __| (pipe)__. Bacically -l prints lines in the file.

Once ready with the values script starts arithmetic operation in the formula
Bash not supports direct arithmetic operations so script using __BC (Basic Calculator)__ __BC__allows to perform arithmetic operations with floating points too. syntax for __BC__ starts with __$(echo__ and __|__ with __bc)__ There is another one opetion to use decimal points with __scale__.__scale=2__ will set the decimal points limit to 2.

one another operation is also held in this scrip to round up the values to an integer value. for this operation __awk__ command is used.
once the value is ready script checking through the conditions to determine the sutable grade of student for the file.

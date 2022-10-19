printf
Description
The printf function sends formatted output to stdout. A custom _printf() for learning purposes was developed by cohort #9 students Jimmer and Edward Ortiz. _printf() function format string is a character string, beginning and ending in its initial shift state, if any. These arguments are placed using the percentage '%' operator

Resources
Secrets of printfby Don colton https://www.cypress.com/file/54761/download

Authorized functions and macros
write (man 2 write) malloc (man 3 malloc) free (man 3 free) va_start (man 3 va_start) va_end (man 3 va_end) va_copy (man 3 va_copy) va_arg (man 3 va_arg)

Compilation
The code must be compiled this way:

*$ gcc -Wall -Werror -Wextra -pedantic .c

As a consequence, be careful not to push any c file containing a main function in the root directory of your project (you could have a test folder containing all your tests files including main functions)

The main files will include your main header file (holberton.h): #include holberton.h

Use & Examples
Prototype: int _printf(const char *format, ...); Use - General: _printf("format string", var1, var2, ...);



Authors ©
Adan Hazi

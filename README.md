# _printf project
##Desciption
The C library function int printf(const char *format, ...) sends formatted output to stdout. Declaration. Following is the declaration for printf() function.
---
#Requirements:
   * Create your own header file named ``` holnerton.h ```.
   * Specific compilation flag: gcc -Wall -Werror -Wextra -pedantic *.c
   * Authorized functions and macros: { write, malloc, free, va_start, va_end, va_copy, va_arg }
---
##use
* Compile all created source code .c along with ``` holnerton.h ``` using gcc -Wall -Werror -Wextra -pedantic *.c
* call _printf function
---
##Available Format specifier
| Format Specifiers | Description |
--- | --- |
%c  | to print a single character
%s  | to print a string
%d | to print a decimal number
%i  | to print an integer
---
##Examples
``` %c ```:
```
int main (void)
{
        _printf("%c", 'A');
}
```
output
```
$A
```
---
``` %s ```:
```
int main (void)
{
        _printf("%s", "Hello World");
}
```
output :
```
$ Hello World
```
---
```%d ```:
```
int main (void)
{
        _printf("%d", 23);
}
```
output :
```
$23
```
---
##Authors
* **Cedric Mupenzi**
* **Beniyam Legesse**

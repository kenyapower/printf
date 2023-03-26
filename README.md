# 0x11. C - printf   
********************
The project is combine efforts of two ALX students namely, Andrew kim Joseph and Wachira Vincent. We are working on different Printf() functionalities.   

_printf() is a function that performs formatted output conversion and print data. Its prototype is the following:

	int _printf(const char *format, ...)

Where **format** contains the string that is printed. As _printf() is variadic function, it can receives n arguments that replace by n tags written inside the string.

we achieve everything through several tasks as elaborated below:   

## Tasks   

0: Write a function that produces output according to a format.   
	+ Prototype: int _printf(const char *format, ...);   
	+ Returns: the number of characters printed (excluding the null byte used to end output to strings)   
	+ write output to stdout, the standard output stream   
	+format is a character string. The format string is composed of zero or more directives. See man 3 printf for more detail. You need to handle the following conversion specifiers:    
		+ c
		+ s   
		+ %   
		
	+ You don’t have to reproduce the buffer handling of the C library printf function   
	+ You don’t have to handle the flag characters    
	+ You don’t have to handle field width, precison   
	+ You don’t have to handle the length modifier   

1: Handle the following conversion specifiers:   
	+ d   
	+ i   
	+ You don’t have to handle the flag characters, field width, precison and length modifier    

2: Handle the following custom conversion specifiers:   
	+ b: the unsigned int argument is converted to binary   

3: Handle the following conversion specifiers:    
	+ u   
	+ o   
	+ x   
	+ X   
	+ You don’t have to handle the flag characters, field width, precison and length modifier    

4: Use a local buffer of 1024 chars in order to call write as little as possible.   

5: Handle the following custom conversion specifier:   
	+ S : prints the string.   
	+ Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)   

6: Handle the following conversion specifier: p.   
	+ You don’t have to handle the flag characters, field width, precison and length modifier    

7: Handle the following flag characters for non-custom conversion specifiers:   
	+ +   
	+ space   
	+ #   

8: Handle the following length modifiers for non-custom conversion specifiers:    
	+ l   
	+ h   
	Conversion specifiers to handle: d, i, u, o, x, X   

9: Handle the field width for non-custom conversion specifiers.   

10: Handle the precision for non-custom conversion specifiers.   

11: Handle the 0 flag character for non-custom conversion specifiers.   

12: Handle the - flag character for non-custom conversion specifiers.   

13: Handle the following custom conversion specifier:   
	+ r : prints the reversed string   

14: Handle the following custom conversion specifier:    
	+ R: prints the rot13'ed string   

15: All the above options work well together.   

------------

## File Functions

### _printf.c
Own Printf Function Tha Performs Formatted Output Conversion And Print Data.

------------

### mainS.h
Header File Were All Prototypes Are Saved.

------------

### get_print_func.c
Pointer To A Function That Selects The Correct Function To Perform The Operation.

------------

### print_buf.c
Function That Prints The Buffer.

------------

### handl_buf.c
Function That Concatenates The Buffer Characters.

------------

### print_chr.c
Function That Writes The Character C To Stdout.
```c
/* identifier : %c */
```

------------

### print_str.c
Function That Writes The String To Stdout.
```c
/* identifier : %s */
```

------------

### print_int.c
Function That Prints An Integer.
```c
/* identifier : %i or %d */
```

------------

### print_bnr.c
Function That Prints Decimal In Binary.
```c
/* identifier : %b */
```

------------

### print_oct.c
Function That Prints Decimal In Octal.
```c
/* identifier : %o */
```

------------

### print_hex.c
Function That Prints Decimal In Hexadecimal.
```c
/* identifier : %x */
```

------------

### print_upx.c
Function That Prints Decimal In Uppercase Hexadecimal.
```c
/* identifier : %X */
```

------------

### print_usr.c
Function That Prints A String And Values Of Non-Printed Chars.
```c
/* identifier : %S */
```

------------

### print_unt.c
Function That Prints An Unsigned Integer.
```c
/* identifier : %u */
```

------------

### print_rev.c
Function That Writes The String To Stdout In Reverse.
```c
/* identifier : %r */
```

------------

### print_rot.c
Function That Writes The String To Stdout In Rot13.
```c
/* identifier : %R */
```

------------

### print_add.c
Function That Prints The Address Of An Input Variable.
```c
/* identifier : %p */
```

------------

### print_long_oct.c
Function That Prints Long Decimal Number In Octal.
```c
/* identifier : %lo */
```

------------

### print_long_hex.c
Function That Prints Long Decimal Number In Hexadecimal.
```c
/* identifier : %lx */
```

------------

### print_long_int.c
Function That Prints  A Long Integer.
```c
/* identifier : %li */
```

------------

### print_long_upx.c
Function That Prints A Long Decimal In Uppercase Hexadecimal.
```c
/* identifier : %lX */
```

------------

### print_long_unt.c
Function That Prints A Long Unsigned Integer.
```c
/* identifier : %lu */
```

------------

### print_short_oct.c
Function That Prints Short Decimal Number In Octal.
```c
/* identifier : %ho */
```

------------

### print_short_hex.c
Function That Prints Short Decimal Number In Hexadecimal.
```c
/* identifier : %hx */
```

------------

### print_short_int.c
Function That Prints  A Short Integer.
```c
/* identifier : %hi */
```

------------

### print_short_upx.c
Function That Prints A Short Decimal In Uppercase Hexadecimal.
```c
/* identifier : %hX */
```

------------

### print_short_unt.c
Function That Prints A Short Unsigned Integer.
```c
/* identifier : %hu */
```

------------

### print_num_hex.c
Function That Print A Number In Hexadecimal Begining With 0 And x.
```c
/* identifier : %#x */
```

------------

### print_num_oct.c
Function That Prints A Number In Octal Begining With 0 And o.
```c
/* identifier : %#o */
```

------------

### print_num_upx.c
Function That Prints A Number In Uppercase Hexadecimal.
```c
/* identifier : %#X */
```

------------

### print_plus_int.c
Function That Prints An Integer With Plus Symbol.
```c
/* identifier : %+i */
```

------------

### print_space_int.c
Function That Prints An Integer Begining With 0 And u.
```c
/* identifier : % i */
```

------------

### ev_print_func.c
Function That Returns The Amount Of identifiers.

------------

### Authors
Andrew Kim Joseph and Nyaga Vincent Wachira.

------------

### End

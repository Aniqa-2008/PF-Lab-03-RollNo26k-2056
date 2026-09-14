| Data Type | Description |
|-----------|-------------|
| int       | Integers are whole numbers that can have zero, positive, and negative values but no decimal values. |
| float     | Floating type variables can hold real numbers with a precision of 6 digits. |
| double    | Floating type variables can hold real numbers with a precision of 14 digits. |
| char      | Character data type allows a variable to store only one character. |
| bool      | A boolean data type that can hold one of two values: true (1) or false (0). |
| void      | A special data type that signifies the absence of a value. It is most often used with functions that do not return a value or with generic pointers. |

| Format Specifier | Description |
|-------------------|-------------|
| %d or %i | Used to print the signed integer value, where signed integer means the variable can hold both positive and negative values. |
| %u | Used to print the unsigned integer value, where unsigned integer means the variable can hold only positive values. |
| %o | Used to print the octal unsigned integer, where an octal integer value always starts with a 0. |
| %x | Used to print the hexadecimal unsigned integer, where the hexadecimal value always starts with 0x. Alphabetical characters are printed in lowercase (a, b, c, etc.). |
| %X | Used to print the hexadecimal unsigned integer, but `%X` prints the alphabetical characters in uppercase (A, B, C, etc.). |
| %f | Used for printing decimal floating-point values. By default, it prints 6 digits after the decimal point. |
| %e / %E | Used for scientific notation. Also known as mantissa/exponent notation. |
| %g | Used to print decimal floating-point values using fixed precision, i.e., the value after the decimal in the input is exactly the same as in the output. |
| %p | Used to print an address in hexadecimal form. |
| %c | Used to print an unsigned character. |
| %s | Used to print strings. |
| %ld | Used to print the long signed integer value. |

| Function | Description |
|----------|-------------|
| scanf() | Reads formatted input from the standard input (keyboard). It can read multiple values of different data types using format specifiers like %d, %f, %c, %s, etc. Stops reading at whitespace, so it can't read strings with spaces. |
| printf() | Writes formatted output to the standard output (screen). It uses format specifiers to print variables of different data types in a specified format. |
| getchar() | Reads a single character from the standard input. It waits for the user to press a key and returns that character as an int. |
| putchar() | Writes a single character to the standard output. It takes one character (as an int) and displays it on the screen. |
| fgets() | Reads a line of text (including spaces) from a specified stream, up to a given number of characters or until a newline/EOF is encountered. Commonly used to safely read strings with spaces from stdin. |
| puts() | Writes a string to the standard output and automatically appends a newline character at the end. |

- Provide examples of at least five escape sequences covered in the lab.
- printf("\n new line my progran");
- printf("\t horizontal tab my progran");
- printf("\" quotations my progran\" ");
- printf("\r carriage return my progran");
- printf("\b backspace my progran");


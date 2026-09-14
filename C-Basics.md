# C Programming Basics

## 1. Data Types

The following table shows some common data types used in C programming.

| Data Type | Description |
|---|---|
| int | Used to store whole numbers such as 10, 25, or -5. |
| float | Used to store decimal numbers with single precision. |
| double | Used to store decimal numbers with higher precision than float. |
| char | Used to store a single character such as 'A' or '7'. |
| bool | Used to store true or false values. |
| void | Represents the absence of a value. |

## 2. Format Specifiers

Format specifiers are used with input and output functions such as `scanf()` and `printf()`.

| Format Specifier | Description |
|---|---|
| %d | Used for signed integers. |
| %u | Used for unsigned integers. |
| %o | Used to display an integer in octal form. |
| %x | Used to display hexadecimal values using lowercase letters. |
| %X | Used to display hexadecimal values using uppercase letters. |
| %f | Used for floating-point values. |
| %e | Used to display floating-point values in scientific notation. |
| %c | Used for a single character. |
| %s | Used for strings. |
| %ld | Used for long signed integers. |

## 3. Input and Output Functions

### scanf()

`scanf()` is used to take formatted input from the user.

Example: `scanf("%d", &number);`

### printf()

`printf()` is used to display formatted output on the screen.

Example: `printf("Number = %d", number);`

### getchar()

`getchar()` is used to read a single character from the user.

Example: `ch = getchar();`

### putchar()

`putchar()` is used to display a single character.

Example: `putchar(ch);`

### fgets()

`fgets()` is used to read a line of text, including spaces.

Example: `fgets(name, 50, stdin);`

### puts()

`puts()` is used to display a string and automatically moves the cursor to a new line.

Example: `puts(name);`

## 4. Escape Sequences

Escape sequences are special characters that begin with a backslash.

| Escape Sequence | Description | Example |
|---|---|---|
| `\n` | Moves the cursor to a new line. | `printf("Hello\nWorld");` |
| `\t` | Inserts a horizontal tab. | `printf("Name\tAge");` |
| `\\` | Displays a backslash. | ` printf("\\");` |
| `\"` | Displays a double quotation mark. | `printf("\"Hello\"");` |
| `\b` | Moves the cursor one position backward. | `printf("ABC\b");` |

## 5. Precision

Precision is used to control the number of digits displayed after the decimal point for floating-point values.

For example, if:

`float number = 12.34567;`

Then:

`printf("%.2f", number);`

will display:

`12.35`

Similarly:

- `%.1f` displays 1 digit after the decimal point.
- `%.2f` displays 2 digits after the decimal point.
- `%.3f` displays 3 digits after the decimal point.
- `%.4f` displays 4 digits after the decimal point.

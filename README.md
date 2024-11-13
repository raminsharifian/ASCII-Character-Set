# ASCII Character Set in C Programming - PDF Guide

This repository contains a PDF document that provides a detailed guide on the **ASCII character set** in C programming, including a breakdown of the ASCII codes and their usage in C code. The document is designed to help developers and programmers understand and utilize the ASCII standard effectively in software development.

## PDF Overview

The guide covers:

- A comprehensive **ASCII chart** with decimal, octal, hexadecimal, and character representations.
- Explanation of **printable** and **non-printable ASCII characters**.
- **Examples in C** for working with ASCII characters.
- How **ASCII** is used in various programming scenarios, including string handling and data transfer.

## Unicode Note

**Note:** In Unicode, the ASCII character block is known as `U+0000..U+007F` and is referred to as **Basic Latin**.

## How to Use the PDF

1. **Download** the PDF file from this repository.
2. **Read through** the sections explaining the ASCII character codes and their uses.
3. **Use the C code examples** provided to implement ASCII handling in your own programs.

## C Code Example

Here’s an example C code snippet included in the guide that demonstrates how to print printable ASCII characters:

```c
#include <stdio.h>

int main(void) {
    puts("Printable ASCII:");
    for (int i = 32; i < 127; ++i) {
        putchar(i);
        putchar(i % 16 == 15 ? '\n' : ' ');
    }
}
```

This code will print all the printable ASCII characters in a structured format.

## License

This document and associated materials are copyright © 1991–2024 Unicode, Inc. and are subject to the **Unicode Terms of Use**. All rights are reserved.

You may **download** and **use** this document for **personal or internal business purposes** only, provided that any copies or modifications fully reproduce all copyright and other legal notices contained in the original publication.

### **Permitted Uses**:

- Personal use
- Internal business use (non-public distribution)

### **Prohibited Uses**:

- Public distribution
- Modifications or adaptations for public use
- Extraction, copying, or redistribution of fonts or font data

For any use outside the permitted scope, please obtain explicit written permission from **"Unicode, Inc."**.

For more information on the Unicode Terms of Use, visit: [https://www.unicode.org/copyright.html](https://www.unicode.org/copyright.html)

## Contact

For any questions, feel free to open an issue or contact the repository owner directly.

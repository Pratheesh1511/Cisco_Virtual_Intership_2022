This Python code allows you to enter up to 10 IPv4 addresses and converts them into their corresponding binary, octal, and hexadecimal representations. It also validates the input addresses to ensure they are in the correct format.
\n
**Functionality:** \n
\n
\n
**Input:** \n
\n
The code starts by prompting the user to enter up to 10 different IPv4 addresses. \n
Each address needs to be entered in the standard format of four numerical parts separated by dots (e.g., "192.168.1.1"). \n
The code includes validation checks to ensure each address is in the correct format:
There are four parts separated by dots.\n
Each part is a valid integer between 0 and 255 (excluding 0 for the first part). \n
If an invalid address is entered, the code displays an error message and prompts the user to re-enter the address. \n
\n
**Conversion:** \n
\n
Once a valid address is entered, the code converts it into three different representations:\n
Binary: Each decimal part of the address is converted to its binary equivalent using string formatting.\n
Octal: Each decimal part is converted to its octal equivalent using string formatting.\n
Hexadecimal: Each decimal part is converted to its hexadecimal equivalent using string formatting.\n
These conversions are stored in separate strings for each address.\n
\n
**Output:** \n
\n
The code then prints the original IPv4 address along with its converted binary, octal, and hexadecimal representations in a well-formatted manner. \n
For example, if you enter the address "192.168.1.1", the output might look like this: \n
Decimal: 192.168.1.1 \n
Binary: 11000000.10101000.00000001.00000001 \n
Octal: 300.250.001.001 \n
Hexa: C0.A8.01.01 \n
\n
**Optional File Saving:** \n
\n
The code also includes an optional feature to save the converted addresses to a text file named conversion.txt. This allows you to easily access the results later on.\n

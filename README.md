This Python code allows you to enter up to 10 IPv4 addresses and converts them into their corresponding binary, octal, and hexadecimal representations. It also validates the input addresses to ensure they are in the correct format.<br>
**Functionality:** <br>
<br>
**Input:** <br>
<br>
The code starts by prompting the user to enter up to 10 different IPv4 addresses. <br>
Each address needs to be entered in the standard format of four numerical parts separated by dots (e.g., "192.168.1.1"). <br>
The code includes validation checks to ensure each address is in the correct format:
There are four parts separated by dots.<br>
Each part is a valid integer between 0 and 255 (excluding 0 for the first part). <br>
If an invalid address is entered, the code displays an error message and prompts the user to re-enter the address. <br>
<br>
**Conversion:** <br>
<br>
Once a valid address is entered, the code converts it into three different representations:<br>
Binary: Each decimal part of the address is converted to its binary equivalent using string formatting.<br>
Octal: Each decimal part is converted to its octal equivalent using string formatting.<br>
Hexadecimal: Each decimal part is converted to its hexadecimal equivalent using string formatting.<br>
These conversions are stored in separate strings for each address.<br>
<br>
**Output:** <br>
<br>
The code then prints the original IPv4 address along with its converted binary, octal, and hexadecimal representations in a well-formatted manner. <br>
For example, if you enter the address "192.168.1.1", the output might look like this: <br>
Decimal: 192.168.1.1 <br>
Binary: 11000000.10101000.00000001.00000001 <br>
Octal: 300.250.001.001 <br>
Hexa: C0.A8.01.01 <br>
<br>
**Optional File Saving:** <br>
<br>
The code also includes an optional feature to save the converted addresses to a text file named conversion.txt. This allows you to easily access the results later on.<br>

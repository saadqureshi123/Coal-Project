# Coal-Project
1.	Introduction:
 A palindrome is a sequence of characters that reads the same forwards and backwards, ignoring spaces, punctuation, and capitalization. Detecting palindromes is a common problem in computer science, often used in string manipulation exercises. In this project, we implemented a palindrome detection program in Assembly Language using the Microsoft Macro Assembler (MASM).


2.Library use:
Our program utilizes several MASM libraries and directives to facilitate string manipulation and user interaction. The primary libraries used include:

Irvine32.lib: This library, provided by Kip Irvine, offers various useful procedures for input/output operations, such as reading strings from the user and displaying messages. It simplifies many tasks in assembly programming.
Kernel32.lib: This Windows API library is used for basic system functions, including memory management and console operations.
These libraries allow our program to handle input and output efficiently and perform necessary string manipulations.

2.	Data Flow Diagram:

     (Start)             
        |
        v

 (Read Input String)

        |
        v

| Process String:           |
| - Remove spaces           |
| - Convert to lowercase    |

        |
        v

| Check Palindrome:         |
| - Compare characters      |
|   from both ends          |
| - If mismatch, not a      |
|   palindrome              |

        |
        v

| Display Result    |
| (using Irvine32)  |

        |
        v

       (End)


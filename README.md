# RegEx-BrainF-Interpreter
A Brainfuck interpreter in RegEx only (using Find/Replace).
# Usage
Use any Editor that can find/replace with RegEx Syntax. I tested this on Notepad++, but since I only used Perl RegEx Syntax, it should also work with other applications.
Create a new file and add the Brainflakes source code on the first line. It must contain a sequence of only the 8 coding BF characters, all on the first and only line:


Use "find and replace" in RegEx mode with the "find" parameter from Find.txt and the "replace" parameter from Replace.txt. Click “replace all” once. This will set up the environment (now 4 lines of code). If the BF code demands input, you have to write it on line 2, AFTER the ‘|’ character.


Now click “replace all” many, many times. Or if you don't want to get cramps, use the keyboard shortcut for “replace all” (in the German 
Version of Notepad++ its alt+T).


The Interpreter will only stop:
- When more user input is needed
- When a HALT state is reached (end of code). It will remove everything except the output and stop replacing.

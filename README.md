#  CLI RPN Calculator
Command-line reverse polish notation (RPN) calculator in Python. In RPN, the operators follow their operands; for instance, to add 3 and 4 together, one would write 3 4 + rather than 3 + 4. If there are multiple operations, operators are given immediately after their final operands

# Details:
This is a simple stack-based implementation. I've used lambda functions, which are built-in functions that tend to run relatively faster. You can also see that the code can be easily extended to include more than the basic 4 statements. How the code can be improved: Instead of using a Python module that behaves like a singleton class, a better approach might be to use a class that can be used to create multiple instances that don't interfere with each other

# Note: 
The calculator exits when it receives a q command or an end of input indicator (EOF / Ctrl+D / Ctrl+Z on Windows)

# Automated Testing
Used unittest - Automated testing framework. The unit testcases include solving a few expressions and error cases. 
## Week 8 Debugging Lab

### Bug 1: KeyError
Error: KeyError: 'amount'

Investigation:
- Ran the Python program in the terminal.
- Inspected the traceback and dictionary keys.
- Used print statements and terminal commands.

Fix:
Corrected the dictionary key reference.

### Bug 2: TypeError
Error: '>' not supported between int and str

Investigation:
- Ran the program again.
- Identified the comparison between an integer and a string.

Fix:
Changed '1000' to 1000.

### Verification
Command: python3 week8_buggy.py

Output:
Total: $5150.00 across 3 records
True

Command: python3 -m pytest -v

Result: 8 tests passed.
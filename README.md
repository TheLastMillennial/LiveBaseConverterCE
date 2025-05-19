# LiveBaseConverterCE
A Base 2, 8, 10, &amp; 16 converter that will display all 4 conversions at the same time immediately.
Made for the TI-84 Plus CE with OS 5.2+

### Instructions:
1. Send all files to your calculator. 
2. Run prgmBASELIVE. 
3. Use the following keymap.

|     Key     | Description |
|-------------|-------------|
| up, down    | change input base (The < character shows which base is the current input base) |
| number keys | input numbers 0-9 |
| math, apps, prgm, x^-1, sin, cos | input letters A-F |
| del   | backspace |
| clear | resets inputs |
| graph | toggles live mode (live mode converts bases when input changes. Otherwise press [enter] to convert) |
| enter | calculate conversion (not necessary in live mode) |
| mode  | quit |

### Custom Base:
To add a custom base between 2-16, edit prgmBASELIVE and add a fifth entry to the list stored to L1. There will be no input validation so use at your own risk.

### Known issues:
- Pressing del with only one character inputted will cause a crash. (use clear in the meantime)
- Using a custom base may cause the text in the bottom right to be partially cleared.

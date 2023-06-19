# SUM_BOLD

An addon for google sheets that allows to sum only values in cells with bold style.

Note that since change of style doesn't trigger recalculate in sheets the result will be updated only when one of the values is edited.

## Usage
You need to pass the address of the first cell as text, then a range of values.
If only the range was passed then the function would get only the values (without information about styles) hence the need for two arguments.

Example: `=SUM_BOLD(CELL("address", C4:J39), C4:J39)`.

Hint: moving the cell with the formula around will also trigger recalculate.

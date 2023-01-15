tsv-utils
=========

Simple POSIX shell utilties for handling TSV (tab-separated values) files.


aligntsv
--------
Aligns the columns of a TSV file by inserting spaces so that every column has
the same width. The output is still in TSV format. This makes it easier to view TSV files in the terminal. Field data must not contain consecutive spaces.

You can set the tab width in your editor to 1 for TSV files and highlight tabs to improve readability.

inscoltsv
---------
Inserts a column before the specified column number. The columns numbers start
at 1. The column's fields will contain "-".

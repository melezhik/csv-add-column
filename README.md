# SYNOPSIS

Add Column to end every line in CSV file using awk.

The author of original awk script is [birei](https://stackoverflow.com/users/773159/birei)
the code is taken from [StackOverflow](https://stackoverflow.com/questions/9506810/add-column-to-end-of-csv-file-using-awk-in-bash-script).

# INSTALL

    $ sparrow plg install csv-add-column

# USAGE

To add `date` value to the end of every line in CSV `$file`:

    $ sparrow plg run csv-add-column \
    --format concise \
    --param file=/path/to/file/example.csv \
    --param data="`date`" > output.csv

# Plugin maintainer

Alexey Melezhik

# Prerequisites

Awk should be installed

# Diceware

The Diceware algorithm was developed by Arnold Reinhold. Please refer to his
explanation and related materials at:

http://world.std.com/~reinhold/diceware.html

The `diceware` script is based on this algorithm and gathers random numbers
generated by atmospheric processes from an online service located at
https://www.random.org/.

## Usage

The program is a bash script and requires bash 4 or greater. To run the script
please execute as follows:

    $ diceware N

where `N` is a positive integer indicating the number of words to fetch. As of
2012 Reinhold recommends six or more. Note that above, the `$` symbol indicates
the bash promt.
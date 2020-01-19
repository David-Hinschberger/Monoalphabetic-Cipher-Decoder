# Monoalphabetic Cipher Decoder

Monoalphabetic Cipher Decoder is a python script that will decipher English monoalphabetic ciphers.

The algorithm used to decipher things is a genetic algorithm, which depends on chance to obtain the most confident
 result.
There are no library dependencies, and the code is from an extra credit project in my Computer and Network Security
 course at UND.

The actual script can take a while to load, depending on the variables, `HILLS` and `STAIRS_PER_HILL`, which are
 variables in the genetic algorithm for iterations.

Included is an input.txt file that works as an example for the script to be tested with.

## Notes
Current code is run with current configuration:
```
HILLS = 50
STAIRS_PER_HILL = 5000
rating_dictionary = ratings.trigrams
```

Project will eventually be updated with [Click](https://click.palletsprojects.com/en/7.x/) to accept CLI arguments.
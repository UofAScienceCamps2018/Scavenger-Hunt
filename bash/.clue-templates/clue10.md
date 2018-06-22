### Clue 10: Pipes ###

#### Piping Information ####

Many commands will print their output. This is called "standard output" or
`stdout`. We saw earlier how you can redirect standard output to a file (`>`).
There is also standard input (`<`). For example, `cat < README.md` is the same
as `cat README.md`. But standard input and output can be chained together using
pipe (`|`). For example, you can count the number of files and folders in a
directory like this:

    ls | wc -w
    
This works by taking the output of `ls` and using it as the input to `wc`.
Another example:

    grep ^sand /usr/share/dict/words | wc -l

will print the number of words that start with "sand". The carat `^` symbol
is a regular expression that means "starts with". You can also use `$` for
"ends with".

#### Sort ####

Sometimes you need to sort data alphabetically. You'll notice that the
dictionary file is already sorted. You can create your own unsorted copy like
this:

    sort -R /usr/share/dict/words > random_words
    
Now you can `sort random_words` to get back to alphabetical order, or 
`sort -r random_words` for reverse alphabetical order. 

Using different flags in the sort command you can sort numerically. Use 
"sort --help to find the appropriate flag. 

#### Finding Clue 11 ####

In the scavenger-hunt folder, there is a file called NHL-Data.txt This file contains the number of assists of each NHL player in the 2013-2014 year. You can open view
this file using "cat [filename]". Using what you have learned in this clue sort the 
NHL data to determine the player with the most assists in 2013-2014. The hint
will be the name of the player with the most assists.
python next_clue.py [secret] 11 [name]. 

    



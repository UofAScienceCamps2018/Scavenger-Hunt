### Clue 9: Searching High and Low ###

#### `grep` ####

Searching files is another useful trick. Try this:

    grep secret README.md
    
This will print out every line that contains the word "secret". `grep` stands 
for Gnu Regular Expression Parsing. Gnu is an umbrella organization that 
publishes open source software. A regular expression is a pattern that matches
text. In this case our regular expression is just "secret", and will only find
exact matches. Regular expressions can be more powerful and/or complicated. For
example,

    grep m.n README.md
    
will find any line where the letters m and n exist with a single character
between them. Check the man page for many interesting features of `grep`.

#### Head / tail  #### 

The head command displays the beginning of a file. The format of the head command is:

	head README.md
	
By default, you can only read the first ten lines of a file. You can change the number of lines displayed by specifying a number option.

	head -50 README.md

The reverse of head is tail. Using tail, you can view the last ten lines of a file. This can be useful for viewing the last ten lines of a log file for important system messages. You can also use tail to watch log files as they are updated. Using the -f option, tail automatically prints new messages from an open file to the screen in real-time.

	tail -50 README.md

#### Finding Clue 10 ####

The next hint is the word that occurs after "tactful" in 
`/usr/share/dict/words`. There's a specific option for `grep` that will make
this easy.


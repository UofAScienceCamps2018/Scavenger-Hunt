# Cryptography Scavenger Hunt

### Rules
1. Asking your peers for help is okay, but try not to copy and paste their code
2. If you get any code from peers or online sources, cite your sources
3. Make sure your code is compatible with Python3 (some things you look up will work for Python2 but not Python3)

#### When you are done
1. Save all of your answers in a file called firstname_lastname_scavenger.txt
2. Call one of the camp leaders over to check your answers

```text
Tem Tamre
Scavenger hunt answers

Puzzle 1: answer1, answer2

Puzzle 2: answer1, answer2, answer3

Puzzle 3: answer1, answer2

Puzzle 4: answer

Puzzle 5: answer

Puzzle 6: answer

Puzzle 7: answer
```

*Hint: Make full use of Github's website functions to find hidden clues*

### Puzzle 1: Caesar Cipher Decryption
You will be given 2 sentences that has been encrypted using a caesar cipher. The first one will be accompanied by the shift number, which should make decryption a lot easier. The second, however, will not come with a key.

```python
ciphertext1 = ""  # Key = 17
ciphertext2 = ""
```

<!--Hint: ciphertext1 is something that we did earlier, ciphertext2 can be solved with a for loop and some printing-->

### Puzzle 2: Substitution Cipher Encryption
You will be given 3 words or phrases that need to be encrypted using the substitution cipher. Come up with a key for each plaintext that will convert them to the expected ciphertext

```python
plaintext1 = "We will stirke Venice"    # Expected ciphertext: 
plaintext2 = "Server shutdown"          # Expected ciphertext: 
plaintext3 = "Build the fort"           # Expected ciphertext: 
```

<!-- Hint: the first two plaintext strings should be encrypted using keys that are in-order -->

### Puzzle 3: Name the cipher
You will be given two encrypted strings. Your job is to figure out which cipher was used to create those encrypted strings

```python
plaintext1 = ""  # Caesar cipher
plaintext2 = ""  # Random substitution cipher
```

<!-- Hint: You can use the same method you used to solve puzzle 1 -->

### Puzzle 4: Three-Rail Cipher
Your job is to learn about the three-rail cipher and use it to encrypt the following plaintext

```python
plaintext = "We should invade the North"
```

<!-- Hint: You don't need to write any code to solve this -->

### Puzzle 5: Vignere Cipher
Your job is to learn about the vignere cipher and use it to encrypt the following plaintext

```python
plaintext = "Riddle me this"
```

<!-- Hint: Just like in puzzle 4, you don't need to write any code to solve this -->

### Puzzle 6: Hidden Message
Decipher the code in the following message:

```text
01 12 23 01 25 19  11 05 05 16  25 15 21 18  16 05 18 19 15 14 01 12  04 01 20 01  19 01 06 05
```

<!-- Hint: Letters can be numbers too -->

### Puzzle 7: Quantum Cryptography (very hard)
Explain (in a few sentences) what quantum cryptography is, in your own words.

<!-- Hint: First, try to figure out what quantum bits are. Then, figure out what quantum computing is. -->

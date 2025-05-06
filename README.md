# Hash-Cracking-Python-
#What is Hash Cracking 
Hash cracking is the process of discovering the original input data (often passwords) that was transformed into a hash using a cryptographic hash function.
ash functions:
- Are one-way (they can't be reversed mathematically).
- Produce fixed-length outputs regardless of input length.
- Are designed to be collision-resistant (two inputs should not produce the same hash).
- Because hashes can't be directly reversed, cracking them involves guessing inputs, hashing those guesses, and comparing them to the target hash

  # Why use Python for this Project
  We chose Python because it's a versatile, beginner-friendly language that excels at automation and scripting tasks like hash cracking. Python offers built-in libraries such as hashlib that support common hashing algorithms making it easy to generate and compare hashes. It also allows us to rapidly prototype custom attacks—like dictionary or brute-force methods.Additionally, Python's readability and wide support for third-party libraries make it ideal for experimenting with various cracking strategies

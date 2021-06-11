# Implementing-GREP-using-Naive-Search-

# What is grep?
```
Grep is a command-line utility for searching plain-text data sets for lines that match a regular
expression or simply a string. E.g.
```
![alt text](https://github.com/HxnDev/Implementing-Linux-CL-Utility-GREP/blob/main/extra/grep_output.png?raw=true)

## Part b:

#### My Grep Algorithm = 248ms

#### My Naïve Algorithm = 366ms

## Reasoning:

- My grep algorithm performed 32.2% better than the naïve algorithm.
- My grep algorithm is more efficient and faster than naïve.
- Naïve only takes one position movement at each time making it
    inefficient.
- In my grep algorithm, it does not match characters that we already
    know will match.
- When naïve finds a position, it does not use it to find another, instead
    it goes back to the starting point and looks for pattern all over again.
- The grep algorithm reuses the information from the previous shift
    rather than disregarding it.
    
#### All the files have been commented for your ease. Furthermore you may also add further comments if you may.

## For further queries contact me at : chhxnshah@gmail.com

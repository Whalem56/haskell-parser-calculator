# haskell-parser-calculator

### Description
Program that resolves numerical expressions and calculates the output.  
Functional programming practice. 
Written in Haskell for my Theory of Programming Languages c

### Usage
Compile: `ghc hw3-problems.hs`  

Run: `hw3-problems.exe`  

##### Operations
- ``-``aExpr
- aExpr ``+`` aExpr (Addition)
- aExpr ``*`` aExpr (Multiplication)
- aExpr ``==`` aExpr (Equality)
- aExpr ``>`` aExpr (Inequality)
- aExpr ``<`` aExpr (Inequality)
- ``If`` bExpr ``then`` aExpr ``else`` aExpr

##### Note
- Overall expression must return a number
- Numbers can be negative

##### Example input and output
> 80 + (-5 * 4)  // 48
> if 1 == 1 then 0 else -1   // 0

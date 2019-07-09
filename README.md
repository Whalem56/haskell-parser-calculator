# haskell-parser-calculator

### Description
Program that resolves numerical expressions and calculates the output.  
Functional programming practice. 
Written in Haskell for my Theory of Programming Languages class.

### Usage
Compile: `ghc hw3-problems.hs`  

Run: `hw3-problems.exe`

##### Parser Grammar
Assume bExpr stands for "boolean expression" and that aExpr stands for "arithmetic expression", then the following grammar holds:
- bExpr := bool | aExpr ``==`` aExpr | aExpr ``<`` aExpr | aExpr ``>`` aExpr
- aExpr := int | ``-`` aExpr | aExpr ``+`` aExpr | ``if`` bExpr ``then`` aExpr ``else`` aExpr


##### Operations
- ``-``aExpr
- aExpr ``+`` aExpr (Addition)
- aExpr ``*`` aExpr (Multiplication)
- aExpr ``==`` aExpr (Equality)
- aExpr ``>`` aExpr (Inequality)
- aExpr ``<`` aExpr (Inequality)
- ``If`` bExpr ``then`` aExpr ``else`` aExpr 


##### Example input and output
- 80 + (-5 * 4)                 // 48  
- if 1 == 1 then 0 else -1      // 0

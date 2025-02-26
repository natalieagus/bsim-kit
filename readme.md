# BSIM Kit

BSIM is the 50.002 Beta CPU simulator. It requires Java to run. Once you have Java installed, open `bsim.jar`. You need to `.include beta.uasm` before typing any beta assembly code.

Here's a sample code that you can run:

```
.include beta.uasm

ADDC(R31, 5, R0)
SUBC(R31, 3, R1)
MUL(R0, R1, R2)
CMPEQ(R1, R1, R4)
CMPLT(R0, R1, R4)
SHL(R1, R1, R5)
SRAC(R5, 4, R5)
SHRC(R1, 4, R6)
```

Click on the Compile button to start the simulation.

Please read the documentation for [BSIM](documentation/bsim.pdf) and [Beta CPU](documentation/beta.pdf) before proceeding.

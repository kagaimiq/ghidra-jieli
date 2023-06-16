# ghidra-jieli

This is the Ghidra processor module for some JieLi's custom CPU architectures.

- dv10 *(this is Blackfin, not implemented)*
- dv12 *(this is Blackfin, not implemented)*
- pi32 *(not complete, but somewhat usable now.)*
- pi32v2 *(very early stage)*
- q32s *(not implemented yet)*
- f59 *(not implemented yet)*
- f95 *(not implemented yet)*

## TODO

- pi32
  - Stack-related instructions (currently only `push {rets}` and `pop {pc}` is handled)
  - Remaining missing instructions
  - rep loops and if-else blocks?
  - Maybe refactor the mnemonics?
  - Change flags on instructions that change them (e.g. add, sub, rotc, etc.)
- pi32v2
  - Do the rest
- q32s
  - Implement it! (at least it's used on BD19 and BD29 - AC632N and AC630N resp.)
- dv10/dv12 (blackfin)
  - Maybe implement it too? Or leave it as a separate project?

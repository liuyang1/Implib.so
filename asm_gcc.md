# using as

- pushq         push value to stack
- popq          pop value from stack

## 7.10 CFI directives
    https://sourceware.org/binutils/docs/as/CFI-directives.html

- .cfi_startproc    start function
- .cfi_endproc      a function END

- .cfi_def_cfa_offset [offset]
    change rule for computing CFA? based on absolute address
- .cfi_adjust_cfa_offset [offset]
    change rule for computing CFA? based on relative offset

- .cfi_rel_offset
- .cfi_restore

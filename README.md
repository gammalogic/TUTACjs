# TUTACjs
A JavaScript implementation of the TUTor Automatic Computer (TUTAC), a theoretical computer designed to aid understanding of computers and computer programming techniques. The design of TUTAC was detailed in the 1964 book "Computer Programming Techniques" by Theodore G. Scott, originally published in the US by U.S. Industries, Inc. and in Great Britain by Macdonald & Co. (Publishers) London. Please note that this simulation uses a reduced subset of the total available opcodes as described in this book to keep it in accordance with the model described in an earlier book by the same author[1].

## TUTAC Machine Specification
- 2000 cell memory (addresses 0000-1999) with 11 digits per cell (1 sign digit, 10 magnitude digits)
- 13 opcodes
- IBM card reader support
- All memory areas are writable at runtime, allowing for self-modifying code

[WORK IN PROGRESS]

## NOTES

[1] TUTAC was originally described in the 1962 book "Basic Computer Programming", also by Theodore G. Scott, originally published in the US by Doubleday & Company, Inc., Garden City, N.Y. The 1962 book describes a total of 13 opcodes, while the 1964 book builds upon this set of opcodes as well as detailing interfaces for front panels, magnetic storage, line printers, etc. The 1964 book also describes a prototype assembler language, the implementation of which is beyond the scope of this project currently.

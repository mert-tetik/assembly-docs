# assembly-docs

Assembling an assembly code

-Requirements
-An assembler for the binaries
-A linker for the executable

On Linux x64
(NASM as the assembler)
(ld for the dynamic linker)
```
    $ nasm -f elf64 -o app.o app.asm
    $ ld -o app app.o
    $ ./app
```

On Linux x86
(NASM as the assembler)
(ld for the dynamic linker)
```
    $ nasm -f elf32 -o app.o app.asm
    $ ld -o app app.o
    $ ./app
```
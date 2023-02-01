# assembly-docs

Assembling an assembly code


Install the NASM via ubuntu terminal
```
    $ sudo apt-get -y install nasm
```

On Linux x64
(NASM as the assembler)
(ld as the dynamic linker)
```
    $ nasm -f elf64 -o app.o app.asm
    $ ld -o app app.o
    $ ./app
```

On Linux x86
(NASM as the assembler)
(ld as the dynamic linker)
```
    $ nasm -f elf32 -o app.o app.asm
    $ ld -o app app.o
    $ ./app
```
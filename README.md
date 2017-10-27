# Bootloader
Tiny 32-bit x86 operating system kernel

From Alex Parker's exceptional (and tiny) series of articles:

[Writing a Bootloader Part 1](http://3zanders.co.uk/2017/10/13/writing-a-bootloader/)

[Writing a Bootloader Part 2](http://3zanders.co.uk/2017/10/16/writing-a-bootloader2/)

[Writing a Bootloader Part 3](http://3zanders.co.uk/2017/10/18/writing-a-bootloader3/)

## Prerequsites
[nasm](http://www.nasm.us/)
[QEMU](https://www.qemu.org/)

## tl;dr
1. compile - `nasm -f bin <file>.asm -o <file>.bin`
2. run - `qemu-system-x86_64 -fda <file>.bin`

# genexp
Simple pwn exploit template generation tool.
Generates a file `exp.py` in the folder in which it's run.
If you're too lazy to write scripts from scratch, and you think pwntools' default exploit template sucks, this is for you.

## Installation
For usage anywhere, add the directory which its in to your `$PATH` or cp to `/usr/bin`

## Usage
```sh
genexp.py [-h] --binary/-b BINARY [--remote/-ip REMOTE] [-port/-p PORT] [--libc/-l LIBC] [--arch/-a ARCH]
```

# forth-mecrisp-riscv

## Intent

To document setting up and usage of [Mecrisp Quintus](https://mecrisp-stellaris-folkdoc.sourceforge.io/gd32vf103.html), an experimental forth for Risc V microprocessors.

## Introduction

Forth on modern embedded processors has seen some developments for FPGA's, Arm, Risc V, ESP 32 and so on.
These are often, but not always, used on hobbyist single board computers based on the Arduino form factor.
Risc V is one of these microprocessors/microcomputers that come in 32 and 64 bit variants. 
This document will test the state of development of one forth, [Mecrisp Quintus](https://mecrisp-stellaris-folkdoc.sourceforge.io/gd32vf103.html), out of 3 such Forth distributions.

## Development Environment

Debian in a Docker Container hosted on MacOS.

Start the container:

```bash
docker run 
    --name forth-mecrisp-riscv \
    -h forth-mecrisp-riscv \
    -v /host_mnt/Users/<user-name-here-0>/development/mecrisp:/home/<user-name-here-1>/src \
    -e LANG=C.UTF-8 \
    -it debian  
    /bin/bash -l
```


## Resources

| *Resource* | *URL* |
| Download |  [Mecrisp Quintus](https://sourceforge.net/projects/mecrisp/ |

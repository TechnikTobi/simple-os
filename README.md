# simple-os
Some playing around with different ideas &amp; technologies regarding the project of writing a small OS. 

## Resources
- [MikeOS](https://mikeos.sourceforge.net) and its [simplified version](https://mikeos.sourceforge.net/write-your-own-os.html). Focuses on 16-bit x86.
- The [initial commit of newOS](https://github.com/travisg/newos/commit/9f8ca17c57099eacac49ae707f0cd9ab700d5169#diff-f06ba4e6ae5b13cb787bad05af2c231bcf826410f25bfd78b18774115f0d20a8), a succesor of BeOS and the base for Haiku.
- [Writing an OS in Rust](https://os.phil-opp.com)
- A project for a Rust-written OS on RISC-V: [Link](https://osblog.stephenmarz.com) 
- [The little book about OS development](https://littleosbook.github.io)
- [Operating Systems: From 0 to 1](https://github.com/tuhdo/os01)
- [The OSKit Project](https://www-old.cs.utah.edu/flux/oskit/)
- The osdever forums [tutorials](http://www.osdever.net/tutorials/) and [papers](http://www.osdever.net/papers/) 
- Bran's Kernel Development: [bkerndev](http://www.osdever.net/bkerndev/index.php)
- [OSDev.org](https://wiki.osdev.org/Main_Page)
- The Kernel [101](https://arjunsreedharan.org/post/82710718100/kernels-101-lets-write-a-kernel) and [201](https://arjunsreedharan.org/post/99370248137/kernels-201-lets-write-a-kernel-with-keyboard) tutorials
- [6.828](https://pdos.csail.mit.edu/6.828/2018/overview.html)
	- [6.S081: Xv6, a simple Unix-like teaching operating system](https://pdos.csail.mit.edu/6.828/2021/xv6.html)
	- [Xv6: Sources and Text](https://pdos.csail.mit.edu/6.828/2012/xv6.html#v6)

### Videos
- [Operating System using Rust and aarch64 - The beginnings (1)](https://www.youtube.com/watch?v=E1pzQw5N_pU)
- [chill kernel hacking for fun](https://www.youtube.com/watch?v=YcmwsJU1S0E)
- [90 days of making my own operating system](https://www.youtube.com/watch?v=kJhs4nlpRiY)
- [Building a Operating System](https://www.youtube.com/watch?v=hti0h_WAkog)
- nanobyte: Building an [OS](https://www.youtube.com/watch?v=9t-SPC7Tczc&list=PLFjM7v6KGMpiH2G-kT781ByCNC_0pKpPN) / [Bootloader](https://www.youtube.com/watch?v=9t-SPC7Tczc&list=PLFjM7v6KGMpjWYxnihhd4P3G0BhMB9ReG)

## QEMU
As a basic, local "machine" for running and testing code before moving to any "real" metal (e.g. RPi, RISC-V controller, etc.). Installing on macOS: 

```brew install qemu```

As of 2025-03-11 this installed 9.2.2. 



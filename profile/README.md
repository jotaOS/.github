<!--<p align="center">
  <img src="https://github.com/jotaOS/.github/raw/master/profile/imgs/banner.png">
</p>-->

Strife is an x86-64 microkernel operating system made in C++ from scratch. It doesn't aim to be a substitute for any existing one, but:

- It's an exercise for myself
- It's a way to show the feasibility of the different ideas I propose
- Not long ago, I decided it to be my TFG (final undergraduate project)

Strife is, according to Empedocles, the force that separates the elements.

The whole project aims to be three things:

- Secure. It makes some already existing security measures as non-optional (ASLR, RELRO, NX stack...). Plus, the whole memory layout of the kernel is designed to be resistant to Meltdown and Spectre attacks.
- Beautiful. When possible and appropiate, Strife gives simple solutions to complex problems, even if they're not the absolute fastest. I've done my very best to write easy to read code. Note, however, that the code is not a tutorial, do not take everything I do as the best solution, or even a good one. Have your own judgment.
- Modular. Strife is not, unlike most hobbyist operating systems, a repository with thousands of files that all have to be compiled in order to get an ISO. It is an anarchic collection of drivers, services, tools, and a kernel, of course. Because of this, you choose what goes in and what's left out. A distribution is, hence, mandatory. An official one is given (link at the end of this README), which bundles _everything_.

The only parts that are not written by me are the bootloader (currently using [Limine](https://github.com/limine-bootloader), which I recommend), and the userspace allocator (Durand's `liballoc`, which I will probably change in the future).

Lost? Understandable. There are a lot of repositories here. Ignore the list of GitHub and [click here](https://github.com/Strife/projects).

This is fruit of many years of research and debugging. It's the work of my life. Do not undervalue the thousands of hours of effort put into this project.

[Click here to begin.](https://github.com/Strife/Strife)

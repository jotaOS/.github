<p align="center">
  <img src="profile/imgs/banner.png">
</p>

jotaOS is an x86_64 microkernel operating system made in C++ from scratch. It doesn't aim to be a substitute for any existing one, but:

- It's an exercise for myself
- It's a way to show the feasibility of the different ideas I propose
- Not long ago, I decided it to be my TFG (final undergraduate project)

The whole project aims to be two things:

- Secure. Mainly due to compartmentalization (each process has its own local view of the system), but also making some already existing security measures as non-optional (ASLR, RELRO, NX stack...). Plus, the whole memory layout of the kernel is designed to be resistant to Meltdown and Spectre attacks.
- Beautiful. When possible and appropiate, jotaOS gives simple solutions to complex problems, even if they're not the absolute fastest. I've done my very best to write easy to read code. Note that the code is not a tutorial, do not take everything I do as the best solution, or even a good one. Have your own judgment.

This is a full operating system, not a kernel or a Linux distribution. It has its own microkernel and userspace, with drivers, services, and tools. The only parts that are not written by me are the bootloader (currently using [Limine](https://github.com/limine-bootloader), which I recommend), and the userspace allocator (Durand's `liballoc`, which I will probably change in the future).

This is fruit of many years of research and debugging. It's the work of my life. Do not undervalue the thousands of hours of effort put into this project.

[Click here to begin.](https://github.com/jotaOS/jotaOS)

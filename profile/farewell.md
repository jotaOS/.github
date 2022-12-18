# Farewell
I've been interested in operating systems for most of my life. I think I was 10 when I got into virtual machines and trying out old Windows versions,
and some years later a few GNU/Linux distributions.

I wanted to write an OS since I was 13 or so. When I didn't know better, I made a fullscreen Windows-looking form in Visual Basic 6.

As I started to learn other languages, I fiddled with [Cosmos](https://www.gocosmos.org/docs/develop-your-own-os-in-dotnet/), a framework of sorts to write
kernels in C#. This made me feel in control, since now I could boot an image and, in absence of a kernel, write lines to screen.

I tried plenty of times to learn assembly so I could make a bootloader and have full control as soon as possible, and failed all of them. When I was 18, I
finally had enough knowledge to understand how an x86 CPU works, so I could learn asm with the help of [SASM](https://dman95.github.io/SASM/english.html).

Once I knew assembly, I felt ready to start writing a kernel, which would then turn into a monolithic OS, `jotadOS`, later renamed to `jotaOS`. The code of
this project is available in the [`old` branch](https://github.com/the-strife-project/Strife/tree/old) of Strife. I started a new one later, with a
microkernel, which would come to have most of the ideas that are present in the code nowadays. A few months in, I renamed it `Strife`.

Strife (including jotadOS and jotaOS) was my main project for more than three years. It turned later into my bachelor thesis, which you can read
[here](https://jlxip.net/theses).
This made me work on it day and night for two months with enormous levels of stress, but I finished it. Strife is able to run simple programs that interact
with the kernel and the running services. The most interesting thing it can do is create files, directories, and manage their permissions.

I meant to keep working on it, but I've come to realize that's not what I want to do with my time. So, I hereby mark Strife as _completed_,
even with all its bugs (mainly memory leaks). It's finished and archived for the rest of time.

I've started a new OS project, (name here when it comes), which takes some of the ideas of Strife, but does most of the things from a completely opposite perspective.

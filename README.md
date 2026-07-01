# Hi, I'm Elijah 👋

I've been writing software for close to twenty years, and I still get most excited about the stuff closest to the metal: lock-free data structures, memory reclamation, compiler tooling, realtime audio. Anything where you have to think about what the CPU and the cache are really up to.

Most of what lands here is Nim and Python, with C when I need it. I'm a big Nim fan: it reads like Python, has metaprogramming that actually delivers, and compiles to small fast native code. If you've run into one of my libraries or gotten a patch from me somewhere, this is the person behind it.

### A few things I've built
- **[`lockfreequeues`](https://github.com/elijahr/lockfreequeues)** - eight lock-free queues in Nim (every producer/consumer combination), with the ordering and progress guarantees properly worked out. The project I've learned the most from.
- **[`nim-debra`](https://github.com/elijahr/nim-debra)** - epoch-based memory reclamation, the piece that makes those queues safe to reclaim without locking.
- **[`python-autopxd2`](https://github.com/elijahr/python-autopxd2)** - turns C/C++ headers into Cython `.pxd` files via `libclang`. I took it over and rebuilt it around clang so it copes with real-world headers, not just the easy ones.
- **[`ringbuf`](https://github.com/elijahr/ringbuf)** - a lock-free ring buffer for realtime DSP in Python, for when the audio callback can't afford to allocate, lock, or wake the GIL.
- I'm a big contributor to **[`run-on-arch-action`](https://github.com/uraimo/run-on-arch-action)**, which a lot of projects use to run CI on non-x86 chips (ARM, riscv64, s390x, and friends).
- **[`axiomantic`](https://github.com/axiomantic)** is my org for AI developer tooling and whatever else I'm nerding out on.

### Away from the editor
I DJ, tinker with electronics, and spend a lot of time on audio and DSP.

Currently open to work, especially anything systems- or audio-shaped. Want to talk shop or think I'd fit something? [LinkedIn](https://www.linkedin.com/in/elijahru) · elijahr@gmail.com

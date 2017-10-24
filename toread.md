
# Papers To Read
## taint analysis
#### [libdft: Practical Dynamic Data Flow Tracking for Commodity Systems](https://github.com/njuwangzhilong/ReadPaperList/blob/master/papers/libdft.practicadynamicdataflowTracking.pdf) [*open source*](https://github.com/njuwangzhilong/ReadPaperList/tree/master/projects/libdft-3.1415alpha)
**<font color=blue>abstract</font>** Dynamic data flow tracking (DFT) deals with tagging and tracking data of interest as they propagate during program execution. DFT has been repeatedly implemented by a variety of tools for numerous purposes, including protection from zero-day and cross-site scripting attacks, detection and prevention of information leaks, and for the analysis of legitimate and malicious software. We present libdft, a dynamic DFT framework that unlike previous work is at once fast, reusable, and works with commodity software and hardware. libdft provides an API for building DFT-enabled tools that work on unmodified binaries, running on common operating systems and
hardware, thus facilitating research and rapid prototyping. We explore different approaches for implementing the low-level
aspects of instruction-level data tracking, introduce a more efficient and 64-bit capable shadow memory, and identify (and avoid) the
common pitfalls responsible for the excessive performance overhead of previous studies. We evaluate libdft using real applications
with large codebases like the Apache and MySQL servers, and the Firefox web browser. We also use a series of benchmarks and utilities
to compare libdft with similar systems. Our results indicate that it performs at least as fast, if not faster, than previous solutions, and
to the best of our knowledge, we are the first to evaluate the performance overhead of a fast dynamic DFT implementation in such
depth. Finally, libdft is freely available as open source software.

---
permalink: /LINKS/
---

Operating Systems 2021-2
---
[HOME](..) | [LINKS](https://bienreti.github.io/os212/LINKS) | [RANK](/TXT/myrank.txt) | [LOG](TXT/mylog.txt) | [GitHub](https://github.com/bienreti/os212)

## LINKS

Hello, this is my collection of sites that i find interesting and helpful. **Most recently added links will be on top of the list**.

#### 1. [Pointers, Stack & Heap Memory, malloc() (pdf)](https://people.cs.clemson.edu/~jmarty/courses/commonCourseContent/Module2-ProgrammingReview/MemoryAndMalloc.pdf)

This pdf introduced pointer variables, demonstrated pointer pass-by-value vs pass-by-reference, pinpointed out what is stored in stack and what is stored in heap, chronologically ordered the stack and heap storing mechanism, and summarized what malloc() and free() does. What makes this pdf so good is that it provided an example for each of those topics and all are explained in just 4 pages!

#### 2. [Pointer Arithmetic and Indexing, NULL and Void Pointer, and L-R Values (pdf)](http://web.cse.ohio-state.edu/~reeves.92/CSE2421au12/SlidesDay12_13.pdf)

Prerequisite: basic understanding of pointer. This pdf which is just 10 slides showed the difference of increment then dereference vs dereference then increment and how much the increment value will be depending on its pointer data type (this is extremely important to know since it is so tricky). It also showed how pointer and array is so similar in some ways. Furthermore, this pdf listed what you can (and can't) do with void pointer also described the NULL usage in pointers. Another thing that this pdf has is that this pdf gave what expression can be occupied (the L value) and what can occupies (the R value), but note that this information need not to be memorized if one can find such pattern. 

---

#### 3. [Fragmentation, External Fragmentation, Internal Fragmentation, first fit, best fit, worst fit in operating systems (OS)](https://t4tutorials.com/fragmentation-external-fragementation-internal-fragmentation-in-operating-systems-os/)

This article provides an intuitive example that helped my understanding of disk fragmentation. Namely, internal fragmentation and external fragmentation.

#### 4. [File System Concept (YouTube)](https://www.youtube.com/watch?v=mzUyMy7Ihk0)

A very brief introduction to file system that is actually easy to understand.

#### 5. [File System Implementation (pdf)](https://graphics.stanford.edu/~tolis/courses/csci4534-04-spring/lectures/8/ch12.pdf)

Complete and brief (only 12 slides) source about Virtual File Systems (VFS), file allocation methods, folder implementation, free-space management, directory block placement, and recovery.

#### 6. [File Allocation Table (YouTube)](https://www.youtube.com/watch?v=V2Gxqv3bJCk)

File Allocation Table (FAT) is one of the most simple and was primarily used file system back in the 70s particularly in Microsoft from DOS until Windows XP. Later, this file system is replaced by the NTFS file system. Because of all of that, learning how FAT works will give you the basic idea of file system. This video provides a good and brief explanation to it.

#### 7. [NTFS and MFT (YouTube)](https://www.youtube.com/watch?v=h8Mb55ox5OE)

NTFS is the file system for newer Windows version, Windows 7 and Windows 10 for example. The video is the most comprehensive video that covers a good portion of NTFS and MFT all across the internet. The video explains in detail, the differences of NTFS and FAT, the relation between MFT and NTFS, and illustrate the idea behind NTFS. 

#### 8. [Inode Structure (YouTube)](https://www.youtube.com/watch?v=tMVj22EWg6A)

Enough for Windows. This video explains very clearly the EXT or Linux's file system. It mainly talks about the Inode or index node structure which is the big part of the EXT file system.

#### 9. [Hard links and Symbolic links — A comparison](https://medium.com/@307/hard-links-and-symbolic-links-a-comparison-7f2b56864cdd)

If you are confused with inode, then this will makes it clearer what inode likes in the user's point of view explained using hard and symbolic links. 

#### 10. [Scheduling Policies - Georgia Tech - Advanced Operating Systems (YouTube)](https://www.youtube.com/watch?v=fQin6dsYTdE)

Explains the possible varieties of how the processor decides which thread to be processed first.

---

#### 11. [The unsolved math problem which could be worth a billion dollars (YouTube)](https://www.youtube.com/watch?v=8COArd_EREw)

The video taught me what SHA256SUM, the most commonly computed algorithm in the world, is. In the video, there is also an explanation of how hash function works, what are the application of SHA256SUM, cool fact about SHA256SUM, and what makes it so important.

#### 12. [Learn VIM while playing a game - VIM Adventures](https://vim-adventures.com/)

A great pixel game that simulates vim controls. By completing this game, you will know the use of b,B,e,E,w,W,x,X and be comfortable using hjkl. There are actually much more than that, but sadly, you have to pay $25. It is still worth to try though if you are going to use vim.

#### 13. [Malware: Difference Between Computer Viruses, Worms and Trojans (YouTube)](https://www.youtube.com/watch?v=n8mbzU0X2nQ)

Don't know what is the difference between types of computer viruses yet? then watch this.

#### 14. [What is PGP/GPG Encryption? In 3 Minutes - PGP/GPG Tutorial for Beginners (YouTube)](https://www.youtube.com/watch?v=1-MPcUHhXoc)

Short video explaining about PGP/GPG.

#### 15. [regex101: build, test, and debug regex](https://regex101.com/)

A very helpful site to try out/hands-on regex without turning on virtualbox and possibly making some mistakes (or dump files).


#### 16. [Pengertian CHMOD dan CHOWN untuk Ganti Permission di Linux](https://www.hostinger.co.id/tutorial/pengertian-chmod-dan-chown-untuk-ganti-permission-di-linux/)

Gives you a basic idea how to grant and remove read, write, execute access of a particular file or directory of which user.

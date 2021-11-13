---
permalink: /LINKS/
---

Operating Systems 2021-2
---
[HOME](..) | [LINKS](https://bienreti.github.io/os212/LINKS) | [TIPS](https://bienreti.github.io/os212/TIPS) | [RANK](/TXT/myrank.txt) | [LOG](TXT/mylog.txt) | [GitHub](https://github.com/bienreti/os212)

## LINKS

Hello, this is my collection of sites that i find interesting and helpful. **Most recently added links will be on top of the list**.

#### 1. [Scheduling Policies - Georgia Tech - Advanced Operating Systems (YouTube)](https://www.youtube.com/watch?v=fQin6dsYTdE)

Explains the possible varieties of how the processor decides which thread to be processed first.

#### 2. [How to use mmap function in C language?](https://linuxhint.com/using_mmap_function_linux/)

Demonstration of mmap function in C.

#### 8. [How to get a file's size in C? (stat, fstat, fileno) (YouTube)](https://www.youtube.com/watch?v=FT2A2HQbTkU)

Concise video about fstat function in C.

---

#### 3. [Introduction of Process Synchronization](https://www.geeksforgeeks.org/introduction-of-process-synchronization/?ref=lbp)

I found this article(s) as a really good place to start learning threads and synchronization. It has a whole section talking about process synchronization. You can check that by looking at the sidebar.

#### 4. [Semaphore in OS | Practice Problems](https://www.gatevidyalay.com/semaphore-in-os-practice-problems/)

Same as above, but this one is for exercise. It also has a set of problems that can be accessed via the sidebar.

---

#### 5. [[03] Processes (pdf)](https://www.cl.cam.ac.uk/teaching/2021/OpSystems/pdf/03-Processes.pdf)

Structured, easy to understand, interactive explanation about process in OS. 

#### 6. [[04] Scheduling (pdf)](https://www.cl.cam.ac.uk/teaching/2021/OpSystems/pdf/04-Scheduling.pdf)

Scheduling explained in the most comprehensible way.

#### 7. [fork() in C](https://www.geeksforgeeks.org/fork-system-call/)

Best explanation of the fork() function on the internet (i guess). Besides clarity, it has many worked examples. Super useful!

#### 8. [Difference Between Fork And Exec](https://programmerbay.com/difference-between-fork-and-exec/)

It is very straightfoward. Good starting point to learn exec function(s). 

#### 9. [An Example Using execlp System Call (pdf)](https://www.albany.edu/~csi402/pdfs/handout_13.3.pdf?__cf_chl_captcha_tk__=pmd_v51.lciKi7KYeRkf8sF9HSBGZ03I_Snrp7CLDYx7jPA-1634094397-0-gqNtZGzNAzujcnBszQil)

A program code that uses every function in W06 demo (except fflush). It has comments about what every function and variable does that rub out my doubts after doing the demos.

---

#### 10. [07 Paging](https://github.com/mor1/ia-operating-systems/wiki/07-Paging)

This article fully explains in detail of paging. For example, it showed the works of page table also listed the pros and cons. It also showed how paging can be optimized using translation lookaside buffer (TLB) and multilevel paging ([Multilevel Paging in Operating System](https://www.geeksforgeeks.org/multilevel-paging-in-operating-system/) very recommended link as an extra to this topic). Later on, this article also explains demand paging, page replacement, frame allocation, and thrashing.

#### 11. [Lecture 13: Demand Paging (YouTube)](https://www.youtube.com/watch?v=4KFZMaCenX4)

(If you prefer the pdf version: [pdf](http://lass.cs.umass.edu/~shenoy/courses/fall14/lectures/Lec15.pdf)). This lecture briefly reviews the last material which is about paging and segmentation then proceed to every important part of virtual memory. What i mean by important is the topic that shows up in the exam and OSC10 chapter 10. This video is what you need if you want to verify as well as strengthen your understanding about demand paging, page fault, and page replacement algorithm.

---

#### 12. [Pointers, Stack & Heap Memory, malloc() (pdf)](https://people.cs.clemson.edu/~jmarty/courses/commonCourseContent/Module2-ProgrammingReview/MemoryAndMalloc.pdf)

This pdf introduced pointer variables, demonstrated pointer pass-by-value vs pass-by-reference, pinpointed out what is stored in stack and what is stored in heap, chronologically ordered the stack and heap storing mechanism, and summarized what malloc() and free() does. What makes this pdf so good is that it provided an example for each of those topics and all are explained in just 4 pages!

#### 13. [Pointer Arithmetic and Indexing, NULL and Void Pointer, and L-R Values (pdf)](http://web.cse.ohio-state.edu/~reeves.92/CSE2421au12/SlidesDay12_13.pdf)

Prerequisite: basic understanding of pointer. This pdf which is just 10 slides showed the difference of increment then dereference vs dereference then increment and how much the increment value will be depending on its pointer data type (this is extremely important to know since it is so tricky). It also showed how pointer and array is so similar in some ways. Furthermore, this pdf listed what you can (and can't) do with void pointer also described the NULL usage in pointers. Another thing that this pdf has is that this pdf gave the list for you of what expression can be occupied (the L value) and what can occupies (the R value), but note that this information need not to be memorized if one can find such pattern. 

#### 14. [Operating System - Memory Management](https://www.tutorialspoint.com/operating_system/os_memory_management.htm)

The article started with the basic idea of memory management. Then, it proceedes by defining logical and physical address (which is an important term). Finally, it demonstrated swapping, fragmentation, paging, and segmentation in very uncomplicated way.

#### 15. [Fragmentation, External Fragmentation, Internal Fragmentation, first fit, best fit, worst fit in operating systems (OS)](https://t4tutorials.com/fragmentation-external-fragementation-internal-fragmentation-in-operating-systems-os/)

Extremely important addition to the last link that can greatly push understanding about OS memory management particularly about fragmentation and memory allocation. This article provided intuitive examples and concise description of disk fragmentation and varieties of memory allocation. 

---

#### 16. [File System Concept (YouTube)](https://www.youtube.com/watch?v=mzUyMy7Ihk0)

A very brief introduction to file system that is actually easy to understand.

#### 17. [File System Implementation (pdf)](https://graphics.stanford.edu/~tolis/courses/csci4534-04-spring/lectures/8/ch12.pdf)

Complete and brief (only 12 slides) source about Virtual File Systems (VFS), file allocation methods, folder implementation, free-space management, directory block placement, and recovery.

#### 18. [File Allocation Table (YouTube)](https://www.youtube.com/watch?v=V2Gxqv3bJCk)

File Allocation Table (FAT) is one of the most simple and was primarily used file system back in the 70s particularly in Microsoft from DOS until Windows XP. Later, this file system is replaced by the NTFS file system. Because of all of that, learning how FAT works will give you the basic idea of file system. This video provides a good and brief explanation to it.

#### 19. [NTFS and MFT (YouTube)](https://www.youtube.com/watch?v=h8Mb55ox5OE)

NTFS is the file system for newer Windows version, Windows 7 and Windows 10 for example. The video is the most comprehensive video that covers a good portion of NTFS and MFT all across the internet. The video explains in detail, the differences of NTFS and FAT, the relation between MFT and NTFS, and illustrate the idea behind NTFS. 

#### 20. [Inode Structure (YouTube)](https://www.youtube.com/watch?v=tMVj22EWg6A)

Enough for Windows. This video explains very clearly the EXT or Linux's file system. It mainly talks about the Inode or index node structure which is the big part of the EXT file system.

#### 21. [Hard links and Symbolic links — A comparison](https://medium.com/@307/hard-links-and-symbolic-links-a-comparison-7f2b56864cdd)

If you are confused with inode, then this will makes it clearer what inode likes in the user's point of view explained using hard and symbolic links. 

---

#### 22. [The unsolved math problem which could be worth a billion dollars (YouTube)](https://www.youtube.com/watch?v=8COArd_EREw)

The video taught me what SHA256SUM, the most commonly computed algorithm in the world, is. In the video, there is also an explanation of how hash function works, what are the application of SHA256SUM, cool fact about SHA256SUM, and what makes it so important.

#### 23. [Learn VIM while playing a game - VIM Adventures](https://vim-adventures.com/)

A great pixel game that simulates vim controls. By completing this game, you will know the use of b,B,e,E,w,W,x,X and be comfortable using hjkl. There are actually much more than that, but sadly, you have to pay $25. It is still worth to try though if you are going to use vim.

#### 24. [Malware: Difference Between Computer Viruses, Worms and Trojans (YouTube)](https://www.youtube.com/watch?v=n8mbzU0X2nQ)

Don't know what is the difference between types of computer viruses yet? then watch this.

#### 25. [What is PGP/GPG Encryption? In 3 Minutes - PGP/GPG Tutorial for Beginners (YouTube)](https://www.youtube.com/watch?v=1-MPcUHhXoc)

Short video explaining about PGP/GPG.

#### 26. [regex101: build, test, and debug regex](https://regex101.com/)

A very helpful site to try out/hands-on regex without turning on virtualbox and possibly making some mistakes (or dump files).


#### 27. [Pengertian CHMOD dan CHOWN untuk Ganti Permission di Linux](https://www.hostinger.co.id/tutorial/pengertian-chmod-dan-chown-untuk-ganti-permission-di-linux/)

Gives you a basic idea how to grant and remove read, write, execute access of a particular file or directory of which user.

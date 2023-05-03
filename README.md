Download Link: https://assignmentchef.com/product/solved-cs342-operating-systems-homework-1
<br>



Please do the following tasks and write a report at the end.




<ol>

 <li>Install the following Linux distribution and release on your own computer: <strong>Ubuntu Desktop 64-bit 18.04 LTS</strong>. It is essential that you install this distribution and release so that you will not have problems  like “was working on my machine”.  You can install Linux on bare hardware, i.e., on a partition of your hard-disk. In this case, make sure you first <strong>backup</strong> all your important data so that you will not loose your data in case your computer does not boot up after installation.</li>

</ol>




You can also install Linux in a <strong>virtual machine</strong> created in your computer. For this, you first need to install a virtualization software, VMware or VirtualBox (or some other virtualization software), on your computer. VirtualBox is free to use.




You can help each other in installing Linux.




You can download Ubuntu 18.04 from:

<ol start="18">

 <li><u>https://releases.ubuntu.com/18.04.5/</u> (<u>64-bit PC (AMD64) desktop image</u>)</li>

</ol>




Write briefly about your installation choices and experiences in your report. After installing Linux, start Linux and learn basic Linux usage. There are lots of guides and tutorials in Internet teaching basic Linux usage. You can benefit from them.  In your report, write down the names of 10 Linux commands that you learned.




<ol start="2">

 <li>Find out and write down the location (pathname) where the kernel executable resides  in the  <em>default</em> directory tree (starting with “/ “) of your Linux installation. Find out the version of your running kernel by using the “uname -r” command. Write the version number in your report.</li>

</ol>




<ol start="3">

 <li>Download the source code of the Linux kernel (from <strong>org</strong>, for example). Download the version that is close to the version of your running kernel. After opening the tar package, change into the root directory of the downloaded kernel source code (it is in the directory where you downloaded the tar package),  and in your report write the names of the subdirectories you see there.</li>

</ol>




<ol start="4">

 <li>In the source code of the kernel, find out the definition of <strong>the system call table</strong>. Write the pathname where you found it. Then, examine the table. Find out the system call names corresponding to system call numbers 5, 43, 123, and 220.</li>

</ol>




<ol start="5">

 <li>Use the <strong>strace</strong> command of Linux to trace the systems calls made by some simple programs like cp, ls, Use the manual page of strace  to learn  more about it (type  man strace). Include sample output in your report. The “man” command provides help pages about Linux commands, system calls,  and C library functions.</li>

</ol>




<ol start="6">

 <li>Use the <strong>time</strong> command to measure the time required to execute some programs like cp, etc. It reports different times: real, user  and sys.  What are they?  Write those values for different program executions.</li>

</ol>




<ol start="7">

 <li>Learn C Programming [1, 2]. Write a simple C program that implements a linked list of integers. Insert 10000 random integers into the list. Make sure you use pointers and malloc(). In your program, measure the time it takes to insert these numbers using the the <strong>gettimeofday</strong>() system call. It gives the current time in microseconds granularity.</li>

</ol>




Write a simple <strong>Makefile</strong> to compile your program. A Makefile is a set of directives and commands specified in a file to compile a project.  The following can be a starting point for your Makefile content. Be careful about TAB characters.

all: list

list: list.c gcc –Wall –g  -o list list.c

clean:

rm -fr list list.o *~




This is useful for you to warm up with C and set up your Linux environment to write C programs. Make sure you do it yourself. Otherwise it will be very difficult to do the projects. You will develop your code in C and  Linux. You will use the gcc compiler.   Include the source code of your program in your report.




<ol start="8">

 <li>Read the first 2 chapters of the textbook this week [3].</li>

</ol>













<ul>

 <li></li>

</ul>
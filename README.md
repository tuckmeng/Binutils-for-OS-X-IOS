# Binutils for OS X and iOS

## Binary utilities for OS X and iOS that runs under Windows
This is a port of binutils for Apple's 2 operating systems (OS X and iOS) that allows you to undertand more about the internals of binaries under them. The tools only work on the executable binaries (ie your OS X and iOS equivalents of the EXE and DLL files). 

A good layman way of telling if the files can be examined under the tools is to see if its executable privilege (set by chmod command in Unix) is set. All executable files would set the executable privilege to be on.

There are not many open source tools that runs in Windows. Most are in Unix or the Mac OS.To compile them to work is a challenge, so I thought I'd save the time for most people who actually prefer to use the tool than to build it.

I built the tools under the Cygwin environment; hence it needs the Cygwin companion binaries attached here to work.

I'm not accepting any commits for now because I want to avoid any concerns on any contaminated code making its way into the binaries.The binaries are not guaranteed to be fit for production use in any way. I'm only using it as a learning tool for myself and making it available to anyone who wants to learn about the internals of OS X and iOS binaries.

# ALWAYS SCAN ANY FILE THAT YOU DOWNLOAD FROM THIS REPOSITORY

Please always scan all files that you download from this repository using your antivirus software or a good one like https://www.virustotal.com. Take the same precautions as you do with any file you download from the internet that you intend to run. Best to always run this in a virtual machine.

# How to use the tools

Please read the documentation under GNU Bintuils. Here's some simple tips to get you started:

- Use "toolname --help" (exclude quotes) to see the options available
- Use "toolname options OSXorIOSbinaryfile" to see data in the binary file. For example, for OS X, osx-objdump -a osx-hello1 gives you the following:

osx-hello1:     file format mach-o-x86-64

# OS X Folder

For the OS X folder, a simple Hello World OS X binary file is stored under osx-hello1. This is used as a test OS X file to try the tools out on.

License
----

All open source licenses belong to their respective software packages (Cygwin and GNU Binaries). Their home pages are as follows:

- Cygwin - https://www.cygwin.com/
- GNU Binutils - https://www.gnu.org/software/binutils/

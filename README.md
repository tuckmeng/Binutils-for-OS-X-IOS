# Binutils for OS X and iOS

## Binary utilities for OS X and iOS that runs under Windows
This is a port of binutils for Apple's 2 operating systems (OS X and iOS) that allows you to undertand more about the internals of binaries under them. The tools only work on the executable binaries (ie your OS X and iOS equivalents of the EXE and DLL files). 

A good layman way of telling if the files can be examined under the tools is to see if its executable privilege (set by chmod command in Unix) is set. All executable files would set the executable privilege to be on.

There are not many open source tools that runs in Windows. Most are in Unix or the Mac OS.To compile them to work is a challenge, so I thought I'd save the time for most people who actually prefer to use the tool than to build it.

I built the tools under the Cygwin environment; hence it needs the Cygwin companion binaries attached here to work.

I'm not accepting any commits for now because I want to avoid any concerns on any contaminated code making its way into the binaries.The binaries are not guaranteed to be fit for production use in any way. I'm only using it as a learning tool for myself and making it available to anyone who wants to learn about the internals of OS X and iOS binaries.

Please always scan all files that you download from this repository using your antivirus software or a good one like https://www.virustotal.com.

License
----

All open source licenses belong to their respective software packages (Cygwin and GNU Binaries). Their home pages are as follows:

- Cygwin - https://www.cygwin.com/
- GNU Binutils - https://www.gnu.org/software/binutils/

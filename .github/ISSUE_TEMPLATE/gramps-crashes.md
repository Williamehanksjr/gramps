---
name: Gramps crashes
about: Geography Crashes Gramps if family tree dialog is closed
title: app crashes
labels: ''
assignees: Williamehanksjr

---

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to 'main menu'
2. Click on 'Geography'
3. Scroll down to '....'
4. See error
-------------------------------------
Translated Report (Full Report Below)
-------------------------------------

Process:               Gramps [987]
Path:                  /Applications/Gramps.app/Contents/MacOS/Gramps
Identifier:            org.gramps-project.gramps
Version:               Gramps-5.1.5-2 (Gramps-5.1.5-2)
Code Type:             ARM-64 (Native)
Parent Process:        launchd [1]
User ID:               501

Date/Time:             2023-07-02 10:43:05.9135 -0700
OS Version:            macOS 13.4.1 (22F82)
Report Version:        12
Anonymous UUID:        CA85C90B-1E9C-A13F-5BD5-0E9B016B8FFB


Time Awake Since Boot: 3500 seconds

System Integrity Protection: enabled

Crashed Thread:        10  pool-Gramps.app

Exception Type:        EXC_BAD_ACCESS (SIGBUS)
Exception Codes:       KERN_PROTECTION_FAILURE at 0x000000016fecc000
Exception Codes:       0x0000000000000002, 0x000000016fecc000

Termination Reason:    Namespace SIGNAL, Code 10 Bus error: 10
Terminating Process:   exc handler [987]

VM Region Info: 0x16fecc000 is in 0x16fecc000-0x16fed0000;  bytes after start: 0  bytes before end: 16383
      REGION TYPE                    START - END         [ VSIZE] PRT/MAX SHRMOD  REGION DETAIL
      Stack                       16fe44000-16fecc000    [  544K] rw-/rwx SM=PRV  thread 10
--->  STACK GUARD                 16fecc000-16fed0000    [   16K] ---/rwx SM=NUL  ...for thread 12
      Stack                       16fed0000-16ff58000    [  544K] rw-/rwx SM=PRV  thread 12

Thread 0::  Dispatch queue: com.apple.main-thread
0   libpixman-1.0.dylib           	   

**Expected behavior**
A clear and concise description of what you expected to happen.

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Desktop (please complete the following information):**
 - OS: [e.g. iOS]
 - Browser [e.g. chrome, safari]
 - Version [e.g. 22]

**Smartphone (please complete the following information):**
 - Device: [e.g. iPhone6]
 - OS: [e.g. iOS8.1]
 - Browser [e.g. stock browser, safari]
 - Version [e.g. 22]

**Additional context**
Add any other context about the problem here.

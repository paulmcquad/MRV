# Malware Research Vlog 5


## Basic Nag removal

```
Lena 151 Tutorial 3 - registerme.exe
SHA-1: 8E74F675EBB1C27EDD95C95CDC6AA935819ED158
```

### Source of information:
[Lenas Reversing for Newbies](https://forum.tuts4you.com/files/file/1307-lenas-reversing-for-newbies)

### Scan & Patch File:

![RegisterMe_EXE1](MRV5_EXE1.jpg)

More info:
[Portable Executable (PE)](../PE.md)

Patch File: [RegisterMe_patch.1337](RegisterMe_patch.1337)


##  Basic + aesthetic patching

```
Lena 151 Tutorial 4 - PixtopianBook.exe
SHA-1: E0E77313C50C5EEA136306A76AE15D5387D66DCE
```
Install (Unpack) + Run Application.

Next waste the trial features.
Try to hunt down the serial.

### Steps:

Step 1: "bp MessageBoxA"
Step 2: Hit "Add Group" Button
Step 3: "Alt + F9" - (Back to User)
Step 4: Close Window
Step 5: At the Function (entrypoint).

### Register

Patch File [PixtopianBook.1337](PixtopianBook.1337)


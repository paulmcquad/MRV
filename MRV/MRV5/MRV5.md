# Malware Research Vlog 5

## Source of information:
[Lenas Reversing for Newbies](https://forum.tuts4you.com/files/file/1307-lenas-reversing-for-newbies)

### Scan File:

![RegisterMe_EXE1](MRV5_EXE1.jpg)

More info:
[Portable Executable (PE)](../PE.md)


```
Lena 151 Tutorial 3 - registerme.exe
SHA-1: 8E74F675EBB1C27EDD95C95CDC6AA935819ED158
```

### Basic Nag removal

Patch File: [RegisterMe_patch.1337](RegisterMe_patch.1337)

###  Basic + aesthetic patching

Install (Unpack) + Run Application.

Next waste the trial features.
Try to hunt down the serial.

## Steps:

Step 1: "bp MessageBoxA"
Step 2: Hit "Add Group" Button
Step 3: "Alt + F9" - Back to User
Step 4: Close Window

## Register

Patch File [PixtopianBook.1337](PixtopianBook.1337)
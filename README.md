# Arch Linux VM Installation

Project for CYB 3353-System Administration at The Univeristy of Tulsa.

Kailey Chinsethagid

Prof. Codi West

## Part 1: Get ISO and verify signature

Download ISO file from trusted source. I got mine from mit.edu.

Generate sha256 checksum of file using the command `Get-FilePath 'filepath'` in Windows Powershell.

- Compare result to verified checksum on the Arch Linux wiki.

## Part 2: Setup Virtual Machine

Using VMware Workstation 17

- Create new virtual machine using ISO download.
- Select `Other Linux 5.x kernel 64-bit` as the operating system.
- Allocate 20 GB to disk size and change memory to 2048 MB.
- 

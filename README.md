# Arch Linux VM Installation

Project for CYB 3353-System Administration at The Univeristy of Tulsa.

Kailey Chinsethagid

Prof. Codi West

## Part 1: Get ISO and verify signature

Download ISO file from trusted source. I got mine from mit.edu.

Generate sha256 checksum of file using the command `shasum -a 256 filepath` in terminal.

- Compare result to verified checksum on the Arch Linux wiki.

## Part 2: Setup Virtual Machine

Using VMware Fusion 12.1.2

- Create new virtual machine using ISO download.
- Select `Other Linux 5.x kernel 64-bit` as the operating system.
- Select `UEFI` boot option.
- In VM settings, change memory to 2048 MB and disk size to 20 GB.
- 

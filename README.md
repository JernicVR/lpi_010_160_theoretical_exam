# LPI 010-160 practice exam

The Linux Essentials certificate is a great way to show employers that you have the foundational skills required for your next job or promotion.

# Installation

## OS X & Linux:
### wget
```sh
# Install via wget
wget -O lpi_010_160_exam.zip https://github.com/Noam-Alum/lpi_010_160_exam.git
unzip lpi_010_160_exam.zip
mv lpi_010_160_exam/lpi_linux.py .
rm -rf lpi_010_160_exam lpi_010_160_exam.zip
```
### git clone
```sh
# Install via git clone
git clone --single-branch --branch main --depth 1 https://github.com/Noam-Alum/lpi_010_160_exam.git && mv lpi_010_160_exam/lpi_linux.py . && rm -rf lpi_010_160_exam
```
<hr>

## Windows:
### wget
```sh
# Install via wget
wget -O lpi_010_160_exam.zip https://github.com/Noam-Alum/lpi_010_160_exam.git
expand lpi_010_160_exam.zip -f:*
move lpi_010_160_exam\lpi_win.exe .
rmdir /s /q lpi_010_160_exam lpi_010_160_exam.zip

```
### git clone
```sh
# Install via git clone
git clone --single-branch --branch main --depth 1 https://github.com/Noam-Alum/lpi_010_160_exam.git
move lpi_010_160_exam\lpi_win.exe .
rmdir /s /q lpi_010_160_exam

```

<br>
<hr>

# Usage example
## This section is reffering to linux users.
### set privileges
Firstly you need to fix the scripts permission
```sh
chmod +x lpi_linux.py
```

### Run the script
After fixing the permissions of the file we can run the script with the following commands:
```sh
./lpi_linux.py
# or
/usr/bin/python3 lpi_linux.py
```
> You must have python3 installed!

<br>

Then you should get the first question of the bunch, e.g. :
```sh
1| What are the differences between hard disk drives and solid state disks? (Choose two.)

Options:

1) Hard disks can fail due to physical damage, while solid state disks cannot fail.
2) Solid state disks can store many times as much data as hard disk drives.
3) /dev/sda is a hard disk device while /dev/ssda is a solid state disk.
4) Solid state disks provide faster access to stored data than hard disks.
5) Hard disks have a motor and moving parts, solid state disks do not.
>
```
<hr>

## This section is reffering to windows users.

### Run the exe file
When running the exe file you should get something along the lines of ```Windows will detect this as a "threat"``` in that case:
1. Press on "More info"
2. Press on "Run anyway"
And you should get the following terminal with the first question of the bunch, e.g. :
```sh
1| What are the differences between hard disk drives and solid state disks? (Choose two.)

Options:

1) Hard disks can fail due to physical damage, while solid state disks cannot fail.
2) Solid state disks can store many times as much data as hard disk drives.
3) /dev/sda is a hard disk device while /dev/ssda is a solid state disk.
4) Solid state disks provide faster access to stored data than hard disks.
5) Hard disks have a motor and moving parts, solid state disks do not.
>
```
### Why?
This is happening because the EXE file is the compiled version of the python code and is not registered in any way, i.e. it does not have a certificate of sort nor vendor information thus making it suspicios,
If you feel concerned running the script that way, feel free to download the python script that is meant for Linux users and run it that way.

## Contact

Noam Alum – [Website](https://ncode.codes) – nnoam.alum@gamil.com

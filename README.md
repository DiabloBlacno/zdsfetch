# zdsfetch-dev![2025-02-26_00-08](https://github.com/user-attachments/assets/877fed4b-f3ef-4ad9-926f-3b6b337e97c7)


Preview(DEV) Version.
NewList:
1. _Added support for Illumos_
2. _Added ASCII Text option. Currently compatible only with OpenIndiana_
An alternative for neofetch and fastfetch
## Compatible with
_Supported fully:Linux, BSD\n
Supported only in DEV version: Illumos\n
Maybe supported: Windows\n_
## Dependencies:
sh (usually pre-installed on unix-like os) or bash
## Build instructions:
Clone repo:
```sh
git clone -b dev https://github.com/diabloblacno/zdsfetch/
```
cd into it
```sh
cd zdsfetch
```
compile main
```sh
sh zdsfetch && chmod +x zdsfetch-dev
```
copy it to /bin and /sbin (/usr/local/bin and /usr/local/sbin on BSD)
```sh
cp zdsfetch /bin /sbin
```
Oh My ZSH users have to rename cloned repository, otherwise it will change directory, not show fetch.
Now it's ready to go!

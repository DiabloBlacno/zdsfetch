![zdsfetch](https://github.com/user-attachments/assets/6687edf1-4f60-4e2f-8056-b4c11505d355)
# zdsfetch
Preview(DEV) Version.
NewList:
1. _Added support for linux-zen, linux hardened, linux-libre and linux-lts_
2. _Added settings for separator and user-separator(separates za dom spremni and username)_

An alternative for neofetch and fastfetch
Dependencies:
Linux or other UNIX-Like OS. Windows not supported.
Works best on Linux and BSD. Other OS marked as unknown
sh (usually pre-installed on unix-like os)
Build instructions:
Clone repo:
```sh
git clone https://github.com/diabloblacno/zdsfetch/tree/dev
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

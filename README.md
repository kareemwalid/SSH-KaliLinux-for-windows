# SSH KaliLinux
A free SSH KaliLinux server without limited time,You can use this for test any tool or using kali linux tools or other something like building custom roms.

You should use vpn while using Hacking Tools like `reconftw,...etc` to avoid ban.
_________________________________________________
# Server specifications
- RAM : `128GB`
- CPU : `AMD Ryzen 7 3700X (16)`
- GPU : `NVIDIA GeForce GT 710`
- Hard Size : `16GB` -->> If you want to increase this, text skyper in telegram and ask him to increase your server space, you can find the telegram group link at the bottom of the repo.
_________________________________________________
# First: Install Packages
_________________________________________________
- You should use this scripts to install packages to connect to server if you using termux or linux,and if you use windows use putty to connect to server with connect command.
______________________

- i made a script for `Linux` and `termux` to install packages and connect to server with very easy way.

- Termux
```sh
curl https://raw.githubusercontent.com/mrx7014/SSH-KaliLinux/main/termux.sh >> termux.sh
bash termux.sh
```

- Linux

```sh
curl https://raw.githubusercontent.com/mrx7014/SSH-KaliLinux/main/linux.sh >> linux.sh
bash linux.sh
```
- Windows

```
1-download mobaxterm for windows and install it
2-press on start-local-terminal
3-write "ssh root@segfault.net "
4-then write "startxvnc"
5-then open new terminal and write " ssh -L5900:0:5900 -o 'SetEnv SECRET={SECRET KEY U GOT}' root@teso.segfault.net"
6-press on session then vnc and write your localhost 127.0.0.1



- Password for connect
```sh
segfault
```
<img src="img/server.png"></a>
______________________________
- Now you connected to server successfully.
- Type this command `bash` after login to use it instade of zsh
```sh
bash
```
______________________________
# You should copy this ssh line from ssh -O to segfault.net
- Like This `ssh -o "SetEnv SECRET=PlPtAROaKlMNmnlsMwSbyb" \root@teso.segfault.net`
- <img src="img/ssh.jpg"></a>
___________________________________________________________________________________
- You must keep this ssh with you, in order to connect to the server using it again. Do not connect using the ssh root@segfault.net command. You must connect using the ssh that you copied in order to save the work that you have done on the server.
___________________________________________________________________________________
# Now if you want to connect to server with vnc server follow steps:
- Type this command in terminal
```sh 
startxvnc
```
- Then it will give you an SSH command again like this
<img src="img/sshvnc.jpg"></a>
- Take this ssh and open it at a new terminal and type passwd
```sh
segfault
```
- Then open any vnc viewer i'm using Remmina who is coming with ubuntu,And put this ip
```sh
127.0.0.1:5900
```
<img src="img/sshdisplay.png"></a>
- Now you are successfully connected to the server with VNC server,Enjoy it.
___________________________________________________________________________________
# Contact US
- Linktree: https://linktr.ee/mrx7014
___________________________________________________________________________________
# Thanks to 
- `Skyper` for this free server
- join his telegram group https://t.me/thcorg
- Website: https://www.thc.org

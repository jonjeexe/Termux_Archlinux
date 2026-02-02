# Termux Archlinux
![Image](https://github.com/user-attachments/assets/612b1141-18ae-41df-8cde-b96f9a7f685b)

Install arch Linux on your mobile using termux without root using proot so follow the instructions given below <br>

# Requirement
- Termux
- Termux:X11 ( optional if you want GUI )
- atleast 2GB free

# Installation
1. Open termux update & upgrade package's
```bash
pkg update && upgrade
```
<br>

2. Install proot-distro in termux
```bash
pkg install proot-distro -y
```
<br>

3. Install arch Linux vie proot-distro

```bash
proot-distro install archlinux
```
<br>

4. Enter into arch linux OS

```bash
proot-distro login archlinux
```
<br>

5. Update arch linux packages

```bash
pacman -Sy
```
<br>

6. Now update all the package into latest version
```bash
pacman -Syu
```
<br>

7. Install xfce4 ( optinal) if you want GUI must install this.

```bash
pacman -S xfce4
```

<br>

8. Install sudo to give permission to the user

```bash
pacman -S sudo
```
<br>

9. Add new user & password with custom username

```bash
useradd -m -G wheel jonjeexe
```
- Now set password of ur new user
```bash
passwd jonjeexe
```

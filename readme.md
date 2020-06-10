# Stick Hero
Stick Hero is a game where you stretch the stick in order to reach the platforms.

This game was developed for the Computer Laboratory class.

It was built as a low-level C application, designed to run on Minix 3 operating system. It uses operating system, kernel and driver level functions to handle keyboard/mouse input, timer/RTC changes and video card output. These device functionalities were done using interrupts (event-driven programming) and polling.


### Instructions
1. Open `minix-lcom/Minix-LCOM.vbox` and set the storage controller to [Minix3.1.8.vdi](https://github.com/rendoir/feup-lcom/releases/download/v1.0/Minix3.1.8.vdi)
2. Enter user `root` and the password `lcom`
3. Copy the repository contents with `scp -r feup-lcom/ root@127.0.0.1/root -P 2222`
4. Copy the configuration file `conf/proj` to `/etc/system.conf.d/`
5. Compile with `make` inside `src`
6. Run with ```service run `pwd`/proj -args `pwd`/..``` inside `src`

- [Optional] Run `ssh root@127.0.0.1 -p 2222` in host OS

# Stick Hero
Stick Hero is a game where you stretch the stick in order to reach the platforms.

This game was developed for the Computer Laboratory class.

It was built as a low-level C application, designed to run on Minix 3 operating system. It uses operating system, kernel and driver level functions to handle keyboard/mouse input, timer/RTC changes and video card output. This device functionalities were done using interrupts (event-driven programming) and polling.


### Instructions
1. Open minix-lcom.vbox and set the storage controller to minix.vdi
2. Enter user *root* and the password *lcom*
3. Clone the repository or copy the contents through SSH
4. Compile `make`
5. Copy config file to `/etc/system.conf.d/`
6. Run ```service run `pwd`/proj` -args `pwd`/..```

- [Optional] Run `ssh root@127.0.0.1 -p 2222` in host OS


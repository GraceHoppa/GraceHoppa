Linux, networks and hardware. I run my own machines from bare metal and build FPV drones with a
soldering iron.

**How I work:** I write the requirements and make the design calls, AI coding agents (Claude Code)
write much of the code, and I test everything on real hardware: my laptop, my PC, an Arduino on an
Android phone. Nothing counts as done until it works on the real machine.

| Project | |
|---|---|
| [hopparch](https://github.com/GraceHoppa/hopparch) | One-script Arch Linux install with a keyboard-first Hyprland desktop. Drivers follow the hardware, every update can be rolled back from the boot menu. Tested in QEMU VMs, runs daily on my laptop. |
| [nanoterm](https://github.com/GraceHoppa/nanoterm) | Flash and talk to an Arduino Nano from an Android phone, no root. C + libusb, CI runs the tests and shellcheck. |
| [fpv-teardown](https://gracehoppa.github.io/fpv-teardown/) | Explorable 3D teardown of my 5" FPV quad. Opens in any phone browser. |
| [hypr-cardboard](https://github.com/GraceHoppa/hypr-cardboard) | Play a PC FPV sim in a phone Cardboard headset. |

Also: a Raspberry Pi running Pi-hole for my home network, set up by hand.

`Arch Linux` `Bash` `systemd` `btrfs + snapper` `LUKS` `ufw` `Pi-hole` `QEMU` `Git + Actions` `Betaflight` `ExpressLRS` `soldering`

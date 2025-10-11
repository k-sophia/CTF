# D12. Final Boss
**Objective:** Discover an IOC in a disk image

**Difficulty:** Hard (500 points)

**Category:** Linux Forensics

## Materials and References
- **Provided:**
    - sd card: `sdcard.img.7z`
    - Resource link: [Linux-Forensics-cheatsheet](https://fareedfauzi.github.io/2024/03/29/Linux-Forensics-cheatsheet.html#disk-imaging-using-dd)
- **Tools Used:**
    - Linux VM
    - Terminal
- **References:**
    - [stackexchange: how-to-mount-a-disk-image-from-the-command-line](https://unix.stackexchange.com/questions/316401/how-to-mount-a-disk-image-from-the-command-line)
    - [stackexchange: can-i-mount-a-partition-from-a-full-drive-image](https://unix.stackexchange.com/questions/230630/can-i-mount-a-partition-from-a-full-drive-image)
    - [losetup](https://linux.die.net/man/8/losetup)
    - [openssl-enc/](https://docs.openssl.org/3.0/man1/openssl-enc/)
    - [umount](https://linux.die.net/man/8/umount)
    - [cryptsetup](https://linux.die.net/man/8/cryptsetup)

## Flag Format
**Format:** a typical IOC value

Example: 
- `https://www.example.com/`
- `0.0.0.0`
- `user@example. com`

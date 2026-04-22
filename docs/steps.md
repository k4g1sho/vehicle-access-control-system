Before we start. Here is my setup.

### Desktop computer
Self built desktop computer for gaming and coding.

Specs:

* CPU: Ryzen 5600x 
* GPU: Ryzen RX6800 
* RAM: 3400MT 2x16GB DDR4 
* Storage: 1TB SSD, 1TB hard drive mounted

### Laptop
Dell


####1. Code and database on the same machine(desktop)

* Desktop OS: Arch linux BTW installed.
* OS installation instruction followed from Arch linux <https://wiki.archlinux.org/title/Installation_guide>
* OS configuration.
   Arch linux, btrfs with snapshorts, 4gb zram.

1. Current installed os-version.
2. Code `cat /etc/os-release` return Arch linux.
3. Code `fastfetch` returns the summarized hardware information.
4. Install postgresql `pacman -Syu postgresql` or yay postgresql with a yay helper found here <>

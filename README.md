# FreeFetch

FreeFetch is a very simple system info tool written in Nim.  
It shows user, host, OS, kernel, CPU, uptime, desktop environment, window manager, and package count.

## How to use

1. Download or clone this repo.  
2. Compile with Nim:
3. Run it, and see your system info.

## Why Nim?

- Nim is easy to learn but very fast.  
- This tool is small and has no big dependencies.

## Features

- Shows username and hostname  
- Shows OS and kernel info (`uname -s -a`)  
- Reads CPU model from `/proc/cpuinfo`  
- Shows uptime in minutes  
- Shows desktop environment and window manager from environment variables  
- Counts packages for Arch Linux pacman users (optional)  
- Cute little ASCII cat logo

## TODO

- Add GPU info  
- Support more package managers  
- Add screen resolution and refresh rate

---

## License

GPL3 License

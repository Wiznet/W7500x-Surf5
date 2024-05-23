# Surf 5 User Guide for Linux (Debian Based)

**Click this [Surf 5 Github Link](https://github.com/Wiznet/W7500x-Surf5/) link to access GitHub, and download the Surf5 project.**

## Installing Build Dependencies

```sh
sudo apt install gcc-arm-none-eabi binutils-arm-none-eabi \
    libnewlib-arm-none-eabi libstdc++-arm-none-eabi-newlib \
    libstdc++-arm-none-eabi-dev \
    gdb cmake make
```

## Start CMAKE generation

Open a terminal into the `W7500x-Surf5` directory :

```sh
cmake -B build
```

Finally go into the `build` directory where the files are generated
and Run `make` to build everything.

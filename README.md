# KAISER: Kernel Address Isolation to have Side-channels Efficiently Removed

This repository contains our implementation of KAISER, a kernel isolation technique to close hardware side channels on kernel address information.
We implemented KAISER as a _proof of concept_ for the Linux kernel and offer a patch as well as pre-build .deb packages.

The [KASLR is Dead: Long Live KASLR](https://gruss.cc/files/kaiser.pdf) [ESSoS 2017](https://distrinet.cs.kuleuven.be/events/essos/2017) paper by Gruss, Lipp, Schwarz, Fellner, Maurice and Mangard.

## Repository Content

| Project  | Description |
| -------- | ------------- |
| [KAISER](KAISER) | Patch to the Linux Kernel |
| [Packages](dist) | .deb packages for Ubuntu 16.10 |

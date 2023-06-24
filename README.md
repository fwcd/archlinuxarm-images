# Arch Linux ARM Images

[![Build Images](https://github.com/fwcd/archlinux-arm-images/actions/workflows/build-images.yml/badge.svg)](https://github.com/fwcd/archlinux-arm-images/actions/workflows/build-images.yml)

Unofficial prebuilt Arch Linux ARM images for several architectures and flavors, primarily intended for use on Raspberry Pis, including some conveniences such as

- Automatic file system expansion on first boot
- Preinstallation of `linux-rpi` and `raspberrypi-bootloader`
- Optional preinstallation of `avahi` (mDNS/DNS-SD) and other tools

These scripts are based on the fantastic work by [andrewboring](https://github.com/andrewboring/alarm-images) and [disconnected.systems](https://disconnected.systems/blog/custom-rpi-image-with-github-travis/#first-stage-script-create-image) on making Arch Linux ARM builds in CI.

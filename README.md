# safertar
A safer way to extract tar archives using fakechroot and chroot

## Overview
Safertar utilizes fakechroot to extract an archive in scenarios where you're uncertain of whether a given version of tar will actually strip leading '/' from paths and prevent overwriting files on the host.

## Usage
```
safertar /path/to/archive.tar
```

# JsonFS

A multi-plaform FUSE that mounts a json as a file system that works on both Linux and OSX.

## Usage

Default usage is as follows:
```bash
jsonfs <json> <mountpoint>
```
See the `-h` or `--help` flag for more details

## Requirements

JsonFS is `python` 3.6+

### Linux

 `fusepy`, and `watchdog` are required.
```bash
pip3 install fusepy watchdog
```

Furthermore, the FUSE kernel module for Linux is required. On Ubuntu:
```bash
sudo apt install fuse
```

### OSX

For OSX: `fusepy`, `pyobjc`, and `watchdog` are required.
```bash
pip3 install fusepy pyobjc watchdog
```

Furthermore, the FUSE kernel module for OSX is required.
```
brew cask install osxfuse
```

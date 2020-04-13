# JsonFS

A FUSE that mounts a json as a file system

## Usage

Default usage is as follows:
```
	jsonfs <json> <mountpoint>
```
See the `-h` or `--help` flag for more details

## Requirements

### Linux

 `fusepy`, and `watchdog` are required.
```
pip install fusepy watchdog
```

Furthermore, the FUSE kernel module for Linux is required.
```
sudo apt install fuse
```

### OSX

For OSX: `fusepy`, `pyobjc`, and `watchdog` are required.
```
pip install fusepy pyobjc watchdog
```

Furthermore, the FUSE kernel module for OSX is required.
```
brew cask install osxfuse
```

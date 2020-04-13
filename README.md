# json-fs
A FUSE that mounts a json as a file system

## Requirements

For OSX, `fusepy`, `pyobjc`, and `watchdog` are required.
```
pip install fusepy pyobjc watchdog
```

Furthermore, the FUSE kernel module for mac is required. This can be found at [https://osxfuse.github.io/](https://osxfuse.github.io/)

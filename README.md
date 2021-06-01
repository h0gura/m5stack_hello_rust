# m5stack_hello_rust


## Getting Started
Update CUSTOM_RUSTC in setenv to point to the version of rust you compiled earlier.
Then load the environment variables with:
```sh
source setenv
```

### Building
Note: Flash operation will also conduct a build.
```sh
cargo xbuild --release
```

### Flashing
```sh
cargo espflash --chip esp32 --release /dev/ttyUSB0
```

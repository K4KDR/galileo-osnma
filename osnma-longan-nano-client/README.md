# osnma-longan-nano-client

This is the host computer serial port client used with the
[osnma-longan-nano](https://github.com/daniestevez/galileo-osnma/tree/main/osnma-longan-nano)
demo of the galileo-osnma library running on a small RISC-V GD32V103 microcontroller.

The instructions for this demo are available in the
[osnma-longan-nano README](https://github.com/daniestevez/galileo-osnma/tree/main/osnma-longan-nano)

### Building

The crate can be built using

```
cargo build --release
```

... and then run from the resulting path using the [demo instructions](https://github.com/daniestevez/galileo-osnma/tree/main/osnma-longan-nano):  
```
galileo-osnma/osnma-longan-nano-client/target/release/
```

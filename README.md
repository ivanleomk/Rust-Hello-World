1. Compile the binary

```
cargo build --target thumbv7em-none-eabihf

```

2. Run it with bootloader

```
qemu-system-x86_64 -drive format=raw,file=target/x86_64-blog_os/debug/bootimage-rust_os.bin
```

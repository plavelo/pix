# pix
A minimum kernel for RaspberryPi.

## Setup

1. [Install Docker](https://docs.docker.com/get-docker/)
1. Ensure your user account is in the [docker group](https://docs.docker.com/engine/install/linux-postinstall/).
1. Prepare the `Rust` toolchain.
   ```
   cargo install cargo-binutils cargo-make
   ```

## Boot the kernel
```
cargo make qemu
```

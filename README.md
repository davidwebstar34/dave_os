rustup override set nightly
cargo bootimage
qemu-system-x86_64 -drive format=raw,file=target/x86_64-dave_os/debug/bootimage-dave_os.bin
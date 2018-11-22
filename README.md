# pre-built images of the Heads Laptop firmware

## source code
The full source code and build instructions for creating the images in
this repository is available at [the Heads git repository](https://github.com/osresearch/heads)
and [it's Wiki](http://osresearch.net/).

## how to use
Flash needs to be writable first. In case you already run a coreboot-based
BIOS, you're fine. If not, the [Skulls project](https://github.com/merge/skulls)
might help you getting started.

Their [release package](https://github.com/merge/skulls/releases)
also includes a `x230_heads.sh` script that you can use to flash these
images.

## how to verify
The Heads firmware images are built reproducibly so anyone can verify the
integrity of the images in this repository. Each archive (build) includes
a text file with the Heads' git hash that is checked out at build-time and
steps to reproduce the exact same image. Verify it by comparing the coreboot.rom
hashes.

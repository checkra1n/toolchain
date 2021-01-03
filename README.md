Universal toolchain
=============
_Low-effort cross-compiling for the masses._


*What's Universal toolchain?*
It's a collection of sysroots and shell scripts in such a way that allows you to build for multiple
architectures. You just need to bring your own Clang.

*Why?*
Not spending the whole time playing around with building multiple compilers.

*What architectures for?*

For Linux:

- arm-linux-musleabi (ARMv5T onwards)
- aarch64-linux-musl (ARMv8-A AArch64)
- x86_64-linux-musl  (AMD64)
- i486-linux-musl (i486 onwards)

For Windows:

- i686-w64-mingw32
- x86_64-w64-mingw32

*What's the catch?*

Apple LLVMs do not have LLD. An LLD is as such included in this repository for macOS use.


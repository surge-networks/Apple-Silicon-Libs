# Apple-Silicon-Libs

This repository contains some common pre-built static libraries for Apple Silicon. All libraries were tested on DTK.

The .a files are universal macOS libraries that contain both arm64 and x86_64 arches.

```
~ file libcrypto.a
libcrypto.a: Mach-O universal binary with 2 architectures: [x86_64:current ar archive random library] [arm64]
libcrypto.a (for architecture x86_64): current ar archive random library
libcrypto.a (for architecture arm64): current ar archive
```

## WARNING!
These libraries were built against Xcode 12 beta 1 for experimental usage. Use it at your own risk.

---

### openssl

Version: 1.1.1g
Built with default configuration.

### openssl

Version: 1.1.1g
Built with default configuration.

### nghttp2

Version: 1.41.0
Build flag: --disable-shared --disable-app --disable-threads --enable-lib-only

### mbedtls

Version: 2.23.0
Built with default configuration.

### libsodium

Version: 1.0.18
Built with default configuration.

# zig-cmake-musl-toolchain
zig cmake musl toolchain

### use
```
cmake  \
  -DCMAKE_TOOLCHAIN_FILE=path/to/zig-musl.toolchain.cmake \
  -DCMAKE_BUILD_TYPE=$BUILD_TYPE -DCMAKE_CONFIGURATION_TYPES=$BUILD_TYPE \
  -DCMAKE_INSTALL_PREFIX=install \
  ..
```
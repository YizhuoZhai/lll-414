For building with llvm toolchain (tested with 3.4.2, 3.8, 3.9, 4.14)
```
make ARCH=x86_64 CC=clang allyesconfig
make ARCH=x86_64 CC=/dir/to/clang-emit-bc.sh
```
Now `allyesconfig` is fine, except KASAN, for statc analysis, please disable KCOV and MODVERSIONS.


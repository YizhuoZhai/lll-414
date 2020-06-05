For building with llvm toolchain (tested with 3.4.2, 3.8, 3.9, 4.14)\
Now `allyesconfig` is fine, except KASAN, for static analysis, please disable KCOV and MODVERSIONS.
```
make ARCH=x86_64 CC=clang allyesconfig
```
Disable the KASAN, KCOV and MODVERSIONS
```
make ARCH=x86_64 CC=/dir/to/clang-emit-bc.sh
```



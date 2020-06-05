This repo contains the clang compilable Linux source code of v4.14.
Now `allyesconfig` is fine, except KASAN, for static analysis, please disable KCOV and MODVERSIONS.
```
$make ARCH=x86_64 CC=clang allyesconfig
```
Disable the KASAN, KCOV and MODVERSIONS
```
$make ARCH=x86_64 CC=/dir/to/clang-emit-bc.sh
```



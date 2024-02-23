# MSYS2

## MinGW64

` gcc mjs_main.c mjs.c -o mjs`



# Linux

## GCC

```bash
gcc mjs.c mjs_main.c -o mjs_mips -ldl

arm-linux-gcc mjs.c mjs_main.c -o mjs_mips -ldl

mipsel-openwrt-linux-gcc mjs.c mjs_main.c -o mjs_mips -ldl
```


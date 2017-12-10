# cross_compile_on_mac

1. add ```elf.h``` and ```elftypes.h``` to ```/usr/local/include```

```sudo ln -s /opt/local/include/libelf /usr/local/include/libelf```


2. kernel/scripts/link-vmlinux.sh

```stat -c %s filename``` --> ```stat -f %z filename```

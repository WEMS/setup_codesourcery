A simple linux script for setting ARM crosscompilation environment with codesourcery.

Originally obtained from: http://www.nas-central.org/wiki/Setting_up_the_codesourcery_toolchain_for_X86_to_ARM9_cross_compiling

Setup Codesourcery
==================

Browseable list of compiler packages: http://sourcery.mentor.com/public/gnu_toolchain/

3 branches containing the versions that WEMS builds against to allow for CI work with Docker

```
$ sudo ./setup.sh
Enter cross comiplation by running: /usr/local/bin/codesourcery-arm-2014.05.sh
$ /usr/local/bin/codesourcery-arm-2014.05.sh
Type 'exit' to return to non-crosscompile environment
NOW in crosscompile environment for arm (arm-none-eabi-)
```

# duktape_nim
A nim binding for Duktape


duktape version: 2.7.0
Nim version: 1.6.2

Re-generate with latest Nim and Duktape. The original project `https://github.com/manguluka/duktape-nim`

To use this binding, user must extract duktape 2.7.0 source files to `duktape/src`. Structure will be like this
```
$ls -R        
.:
total 4.0K
drwxr-xr-x 1 dmknght dmknght  56 Jun 13 14:08 duktape

./duktape:
total 52K
-rw-r--r-- 1 dmknght dmknght 1.7K Jun 13 14:06 duk_config.nim
-rw-r--r-- 1 dmknght dmknght  45K Jun 13 14:06 duktape.nim
drwxr-xr-x 1 dmknght dmknght  100 Jun 13 14:05 src

./duktape/src:
total 3.8M
-rw-r--r-- 1 dmknght dmknght 125K Feb 19 04:22 duk_config.h
-rw-r--r-- 1 dmknght dmknght  51K Feb 19 04:22 duk_source_meta.json
-rw-r--r-- 1 dmknght dmknght 3.6M Feb 19 04:22 duktape.c
-rw-r--r-- 1 dmknght dmknght  74K Feb 19 04:22 duktape.h
```

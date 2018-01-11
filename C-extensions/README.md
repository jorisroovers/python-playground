# Python C extensions

Shamelessly stolen from https://gist.github.com/Artanis/1223762

Building:
```
gcc -fpic --shared $(python-config --includes) greetmodule.c -o greetmodule.so
python helloworld.py
```
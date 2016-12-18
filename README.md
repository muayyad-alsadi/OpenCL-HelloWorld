# OpenCL HelloWorld

Install needed packages, make sure `pkg-config --libs --cflags OpenCL` works.

Type `./build.sh` (you might see some warnings ignore them)

Run `./HelloWorld` 

You should see something like

```
Available Platforms:
0) Intel Gen OCL Driver
1) Clover
2) Portable Computing Language
** Using platform index=0 name=Intel Gen OCL Driver
```

You can override that using

```
CL_PLATFORM_IX=2 ./HelloWorld
```


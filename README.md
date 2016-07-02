# lueve
Eve in C/Lua

## Getting started

### OSX / Linux

Install luajit by downloading [LuaJIT-2.1.0-beta2](http://luajit.org/download.html) and then

```
make
make install
```

then in the `lueve/build` directory:

```
make && ./lueve
```

### Windows

We have a Docker container that runs lueve. You just provide a .eve file to compile and run:
```
docker run -p 8080:8080 witheve/eve [eve_file]
```

Now just point your browser to `http://docker.local:8080/`


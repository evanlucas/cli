## Node.js

### Get number of CPUs

*will show threads if your CPU has hyperthreading*

```shell
$ node -pe 'os.cpus().length'
```

### Profile a node application (CPU)

```shell
$ node --prof app.js
# Look in your cwd for a file named something like isolate-0x102800000-v8.log
$ node --prof-process isolate-0x102800000-v8.log
```

### Check that a js file has valid syntax

```shell
$ node -c file.js
```

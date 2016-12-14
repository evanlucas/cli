## shell

### Print the contents of a file

```shell
# file is named log.txt
$ cat log.txt

# 2 files with a .md file extension
$ cat *.md
```

### Print out the date/time

```shell
$ date
```

### Get a random uuid (v4)

*Only works on OS X*

```shell
# bash shell
$ echo -n $(uuidgen) | pbcopy

# fish shell
$ echo -n (uuidgen) | pbcopy
```

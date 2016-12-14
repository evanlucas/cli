## git

### Get the sha of the tip of the current branch

```shell
$ git rev-parse HEAD
```

### Squash/fixup without using your editor

```shell
$ npm install -g git-fixit
# Will meld the most recent commit into the commit before it
$ git fixit 2
```

### Change a remote url

```shell
# For the origin remote
$ git config remote.origin.url git@github.com:evanlucas/repo
# For the upstream remote
$ git config remote.upstream.url git://github.com/evanlucas/repo
```

```
echo >> feeds.conf.default
echo 'src-git helmiwrtpackage https://github.com/BootLoopLover/helmiwrt-package.git' >> feeds.conf.default
```

```
./scripts/feeds update -a
./scripts/feeds install -a
```

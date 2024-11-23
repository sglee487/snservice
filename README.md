

## how to git submodule update
when folder is empty, init submodules
```bash
git submodule update --init --remote
```

after folder is not empty, update submodules
```bash
git submodule update --remote --recursive
```
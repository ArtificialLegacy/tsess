
# tsess

This is a set of scripts I use for automating `tmux` sessions.

## Usage

Running `tsess` will print out a list of scripts.

If you have a lot of scripts you may want to use `grep` on this output:

```bash
tsess | grep "pers" # search only personal scripts
tsess | grep "work" # search only work scripts
```

Running `tsess script_name` will execute that script.

## Installing / Creating

Create a symlink to `tsess` to a folder on your `$PATH`.

```bash
ln -s ./tsess ~/.local/bin/tsess
```

When creating scripts you may have to `chmod` them:

```bash
chmod +x ./scripts/script_name
```

Scripts can also be in nested subdirectories within `./scripts`.

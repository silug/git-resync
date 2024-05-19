# git-resync

`git-resync` syncs a source git repository to a destination repository.

```
Usage: git-resync [args] source destination

Options:
 -h, --help              This help message
 -m, --mirror            Forcibly re-sync the destination from the source
 -p, --prune             Prune old branches/tags that don't exit on the source
 -t, --onlytags          Only sync tags
 -o <string>,
 --push-option=<string>  Push options
```

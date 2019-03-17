PURPOSE
-------

**btrsnapshot** creates and keeps the latest `NUM` snapshots of `SUBVOLUME` within a btrfs filesystem.

The snapshot will be located at: <DIRNAME>/<SUBVOLUME>/<PREFIX><DATE>

Options:
```
-n, --dry-run          perform a trial run with no changes made
-d, --dirname=DIRNAME  default name is snapshots
-p, --prefix=PREFIX    default is none
-e, --expire=NUM       number of snapshots to keep, default is 7
-c, --clean            do not perform a snapshot - run the expire part only
 --debug            addition debug print
-h, --help             show this help
```

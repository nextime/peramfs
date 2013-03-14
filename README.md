PeRamFS - Permanent Ram File system
====================================

WARNING: THE FILE SYSTEM ISN'T YET FUNCTIONAL. DON'T USE IT!!!
--------------------------------------------------------------

FUSE filesystem copy a real permanent file system in ram and the work completely as 
a commong ramfs, but it has the ability to lock read/write operations to safely copy content
in the permanent storage.

The primary motivation to do that is, for me, to permit to have an InnoDB database 
with all the raw files of the /var/lib/mysql dir on a ramfs.

The initial "fuse python template" is coming from the forked git project "ramfs"

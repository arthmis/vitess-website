---
title: zip
series: zk
commit: 6eddcaeac58bed83ebfa3b9ada903ddc8ff36ff6
---
## zk zip

Store a zk tree in a zip archive.

### Synopsis

Store a zk tree in a zip archive.
	
Note this won't be immediately useful to the local filesystem since znodes can have data and children;
that is, even "directories" can contain data.

```
zk zip <path> [<path> ...] <archive> [flags]
```

### Options

```
  -h, --help   help for zip
```

### SEE ALSO

* [zk](../)	 - zk is a tool for wrangling zookeeper.


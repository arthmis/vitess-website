---
title: touch
series: zk
commit: 6eddcaeac58bed83ebfa3b9ada903ddc8ff36ff6
---
## zk touch

Change node access time.

### Synopsis

Change node access time.
		
NOTE: There is no mkdir - just touch a node.
The disntinction between file and directory is not relevant in zookeeper.

```
zk touch <path> [flags]
```

### Examples

```
zk touch /zk/path

# Don't create, just touch timestamp.
zk touch -c /zk/path

# Create all parts necessary (think mkdir -p).
zk touch -p /zk/path
```

### Options

```
  -p, --createparent   create parents
  -h, --help           help for touch
  -c, --touchonly      touch only - don't create
```

### SEE ALSO

* [zk](../)	 - zk is a tool for wrangling zookeeper.


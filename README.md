Usage
=====

This is a python clone of `backtype.storm.utils.DRPCClient`.

```
from storm.drpc import DRPCClient

c = DRPCClient("my.drpc.host", 3772)
c.execute("wordcounts", "jabberwocky")
```
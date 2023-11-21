# Error in elasticsearch

### 1. Open elasticsearch and kibana
### 2. Try to import csv or any file in kibana from http://localhost:5601
### 3. Error in kibana
### Error creating index
```console
{"name":"TimeoutError","message":"Request timed out"}
```
### 4. Error in elasticsearch terminal
```console
[2023-11-21T20:21:08,680][WARN ][o.e.c.r.a.DiskThresholdMonitor] [Binayaks-MacBook-Air.local] high disk watermark [90%] exceeded on [_d6atLFOQem2Ujwtot8JHg][Binayaks-MacBook-Air.local][/Users/binayakshrestha/Desktop/elasticsearch-8.11.1/data] free: 11.9gb[5.2%], shards will be relocated away from this node; currently relocating away shards totalling [0] bytes; the node is expected to continue to exceed the high disk watermark when these relocations are complete
```

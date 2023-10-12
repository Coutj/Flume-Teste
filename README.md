# Executando spooldir 


```bash
    docker exec -it flume /bin/bash
```

```bash
    flume-ng agent --conf-file /opt/flume-config/flume.conf/spool-to-loer.properties --name agent1 -Dflume.root.logger=WARN.console
```

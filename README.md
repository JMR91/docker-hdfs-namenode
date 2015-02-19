Runs a hdfs namenode in a docker container

## Exposed ports

* TCP   8020    fs.defaultFS                    IPC: ClientProtocol
* TCP   50070   dfs.namenode.http-address       HTTP connector
* TCP   50470   dfs.namenode.https-address      HTTPS connector

## Example

```bash
docker run -d -p 8020:8020 -p 50070:50070 hauptmedia/hdfs-namenode
```


# docker-hive-metastore
A docker image for Apache Hive Metastore standalone

## Usage
```docker run -it -v hive-metastore-vol:/opt/metastore_db -p 9083:9083 cwaffles/hive-metastore```

Metastore is available on port `9083`

## Ephemeral
This container does not persist metastore data between launches

```docker run -it -p 9083:9083 cwaffles/hive-metastore```

### Info
- OpenJDK 11 JRE
- Hadoop 3.3.0
- Hive Metastore 3.1.2
- Derby (backing store)

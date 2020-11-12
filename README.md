# dockerHiveMetastore
A docker image for Apache Hive Metastore standalone

## Usage
```docker run -it -v hive-metastore-vol:/opt/metastore_db -p 9083:9083 hive-metastore```

Metastore is available on port `9083`

## Ephemeral
This container does not persist metastore data between launches
```docker run -it -p 9083:9083 hive-metastore```

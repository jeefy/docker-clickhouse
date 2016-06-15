# docker-clickhouse
A clickhouse docker container for the masses. -- http://clickhouse.yandex

` docker run -p 8123:8123 -p 9000:9000 jeefy/clickhouse `

## Details
Container exposes port 8123 (Native client) as well as 9000 (HTTP client)

To add a custom config, just use a volume!

` docker run -p 8123:8123 -p 9000:9000 -v /your/dir/config.xml:/etc/clickhouse-server/config.xml `

For additional information regarding ClickHouse, head over to their site http://clickhouse.yandex
# simple-clickhouse-cluster


before run docker-compose, set storage chmod 777

` sudo chmod -R 777 */storage`

Подключение к серверам через клиента

`docker-compose exec ch-client bash`

`clickhouse-client --host=ch-server-1 --user=pp_user --password=ABQVtGhg`


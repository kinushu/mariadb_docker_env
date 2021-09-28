# mariadb_docker_env

CentOSで運用されている、MySQL互換DBとして MariaDB のデータダンプを扱いやすいように、docker環境化。
Ruby環境も入れておく。

```shell
docker-compose build
docker-compose up
```

以下のパラメータで接続。

+ host: 127.0.0.1
+ port: 13306
+ user: root
+ pass: secretpass

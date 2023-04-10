# 参考
https://hub.docker.com/r/apache/nifi


# 起動
docker-compose up -d

# 停止
docker-compose down --volumes

# jdbcドライバ
wget -P ./work/jdbc https://jdbc.postgresql.org/download/postgresql-42.2.23.jar

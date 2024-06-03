# dify_docker

## usage

```
git clone https://github.com/iuill/dify_docker.git
cd dify_docker
docker-compose up --build
```

## 備忘

* 公開ポートを変更したいとき
    * `docker-compose.yml` の nginx の Ports のホスト側を変更

* nginx自体のLitenポートを変更したいとき
    * `nginx/conf.d/default.conf` の listen を変更
    * `docker-compose.yml` の nginx の Ports のコンテナ側を変更

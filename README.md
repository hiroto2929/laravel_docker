# dockerでlaravelの環境構築をするときのテンプレ

## 使い方

任意のディレクトリで下記を実行

```
https://github.com/hiroto2929/laravel_docker.git
```

cloneに成功したらlaravel_dockerというディレクトリができるので移動する

```
cd laravel_docker
```

コンテナを立ち上げる

```
docker-compose up
```

コンテナに入る

```
docker exec -it laravel_docker_app_1 bash
```


下記でコンテナから出られる

```
exit
```

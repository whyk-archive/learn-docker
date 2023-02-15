# Chapter 01

既に完成しているDockerコンテナをgit cloneして立ち上げる。

``` bash
git clone https://github.com/suzuki-hoge/docker-practice && cd docker-practice/demo
docker compose up --detach --build
```

確認が終わり次第、以下コマンドでDockerコンテナを落とす。
``` bash
docker compose down
```


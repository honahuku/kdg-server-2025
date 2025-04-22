# kdg-server-2025

## コマンド
```bash
# イメージに名前をつけてビルド
docker build . -t kdg-nginx

# image の一覧を確認する
docker image ls

# 指定した image を実行
docker run -it kdg-nginx


# コンテナの中にいることを確認する
# NAME="Ubuntu" と言われていたらコンテナの中
cat /etc/os-release

# curl コマンドを実行してみる
curl globalip.me
```

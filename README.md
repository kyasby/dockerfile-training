# dockerfile-training

## 概要
- dockerfileを使用して，イメージを作成し，コンテナを立てる
- コンテナでflaskを起動する。
- ホストPCから起動する。

## 詳細
- イメージ名
 - tiangolo/uwsgi-nginx-flask:python3.8
- 以下を実行
 - $ sudo apt update && sudo apt upgrade -y
 - $ sudo apt install vim git
 - 以下のファイルをローカルPCから，dockerの/appにコピー
 - template
 - flask.py
- 起動時コマンド
 - python3 flask_app.py

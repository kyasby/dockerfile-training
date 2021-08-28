# dockerfile-training

## 概要
- dockerfileを使用して，イメージを作成し，コンテナを立てる
- コンテナでflaskを起動する。
- ホストPCから起動する。

## 詳細
- イメージ名
 - tiangolo/uwsgi-nginx-flask:python3.8
- 以下を実行
 - $ apt update && apt upgrade -y
 - $ apt install vim git
 - 以下のファイルをローカルPCから，dockerの/appにコピー
 - template
   - ディレクトリは，"COPY templates/ /app/templates/"でコピー
 - flask_app.py
- 起動時コマンド
 - python3 flask_app.py

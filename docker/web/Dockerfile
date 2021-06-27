# nodeイメージをpullする
# FROM イメージ名:タグ（バージョン）
FROM node:14.15.0-alpine

# working directory
# コンテナ内での作業ディレクトリ名
WORKDIR /app

# vuecliインストール
# コンテナ内で実行するコマンド
RUN apk update && \
    npm install && \
    npm install -g npm && \
    npm install -g vue-cli
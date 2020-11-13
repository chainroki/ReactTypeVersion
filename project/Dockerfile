FROM node:12.18.0-alpine
WORKDIR /usr/src/app

COPY ["package.json", "package-lock.json", "./"]
# パッケージをインストール
RUN yarn install
# ファイルを全部作業用ディレクトリにコピー
COPY . .
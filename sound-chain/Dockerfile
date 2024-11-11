FROM node:18

WORKDIR /app/sound-chain

# 必要なツールのインストール
RUN apt-get update && \
    apt-get install -y git python3 make g++

# グローバルパッケージのインストール
RUN npm install -g yarn hardhat truffle ganache

# 作業ディレクトリの設定
COPY . .

CMD ["/bin/bash"]
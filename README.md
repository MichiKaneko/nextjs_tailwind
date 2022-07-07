# nextjs_tailwind

## 環境構築手順
```
# クローン
git clone git@github.com:MichiKaneko/nextjs_tailwind.git

# 移動
cd ./nextjs_tailwind

# イメージビルド
docker-compose build

# パッケージインストール(初回または、新たにパッケージが導入された時のみ)
docker-compose run --rm front yarn install --frozen-lockfile

# コンテナ起動(バックエンド)
docker-compose up -d
```

## 各種コマンド
```
# コンテナに入る
docker-compose run --rm front sh

# コンテナ起動
docker-compose up
```
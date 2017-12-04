# docker環境構築

## dockerイメージ作成
docker-compose build

## dockerコンテナ起動
docker-compose up -d  
docker-compose ps

## コンソールにアクセス
docker-compose exec web bash

## dockerコンテナ停止
docker-compose down

## dockerイメージを削除する時
docker images  
docker rmi xxx

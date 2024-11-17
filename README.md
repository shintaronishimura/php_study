# php_study

# 環境構築

docker をダウンロードし、git clone したディレクトリ内で「docker-compose up -d」を実行する。
docker exec -it mysql-container bash でコンテナ内の mysql にログインする。
mysql -u root -p で DB に接続する
create_bbs_yt.sql を実行
SHOW TABLES;でテーブルが表示されれば終了

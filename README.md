# 使い方

`docker compose up -d`で起動します。
ログインには

- ホスト: localhost
- ポート: 5432
- ユーザ: postgres
- パスワード: postgres
- データベース: postgres

を使用してください。初回のログインさえ済めば後はロール作るなり`CREATE DATABASE`なりいい感じにしていってください。

compose.ymlと同じディレクトリで`docker compose down`で終了します。

`psql -h localhost -p 5432 -U postgres -d postgres`でデータベースを開きます。

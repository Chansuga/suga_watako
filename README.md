🚀 コマンド一覧
1. イメージをビルドしてコンテナをデタッチドモードで起動
bash
- docker compose up --build -d
2. アプリにアクセス
アプリ画面はこちら
ブラウザで http://localhost:8000/ にアクセスすることでアプリ画面が表示されます。

3. コンテナ内でBashを起動
bash
- docker compose exec web bash
実行後、プロンプトが root@xxxxxxx:/app# となっていれば、Bashが起動しています。
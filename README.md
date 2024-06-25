# angular-tutorial
https://angular.jp/tutorial/first-app
- Angularコマンド一覧

|  内容  |  コマンド |備考|
| ---- | ---- | ---- |
|プロジェクト新規作成|ng new プロジェクト名 --style=scss|プロジェクト作成時に聞かれます。とりあえずこれがいいと思います。Angular routing?：Yes、Which stylesheet：scss|
|モジュール新規作成|	ng g m モジュール名 --routing|	事前に「cd」コマンド|でディレクトリを移動すること|
|コンポーネント新規作成|	ng g c コンポーネント名|	事前に「cd」コマンドでディレクトリを移動すること|
|サービス新規作成|	ng g s サービス名|	事前に「cd」コマンドでディレクトリを移動すること|
|アプリ実行|	ng s -o|	「s」は「serve」の略　「-o」は「open」の略で実行後にブラウザを開いてくれます。|
|アプリ実行|	ng s -o| --port 8888	オプションの「port」はポート番号変更しての実行|
|実行の停止|	Ctrl+C → y|	
|アプリリリースビルド|	ng build --prod|	
|Gitから新規取得後のパッケージのインストール|	npm install	|
|ng serveをiPadで表示|	ng s --host 自分のIP|	iPadから「自分のIP:4200」で接続可能|
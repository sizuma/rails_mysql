# 使い方

以降の作業はすべてリポジトリをカレントディレクトリとして行う

1. `./scripts/up` コンテナの起動

2. `./scripts/rails/new` プロジェクトの作成

3. `./scripts/rails/install` ライブラリのインストール

4. `./scripts/rails/server` サーバの起動(特に何も表示されない)

	http://localhost:3000/ でアクセス可能

PCを再起動したときは1,3,4の手順で起動を行う

`rails generate` などのコマンドを実行するには `./scripts/rails/cli` でコンテナ内に入ってから実行する

ソースコードは `project/` 以下に存在する

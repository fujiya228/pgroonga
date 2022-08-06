# pgroongaを使う環境を整える

1. [direnv/direnv](https://github.com/direnv/direnv)をインストールする
2. .envrcを作成(中身は適宜変更してください。特にDB_USERは変える必要があった)
    ```
    cp .envrc.sample .envrc
    ```
3. direnvを有効化
    ```
    direnv allow .
    ```
4. 起動
    ```
    docker-compose up
    ```
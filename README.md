# docker の WordPress の環境です。ご自由にお使いください。
WordPressのdocker-compose ファイルです。すぐにWordPress環境を構築できます。 AUG/2021 作成


ダウンロードしたフォルダに移動した後

```
 docker-compose up
```

これで動きます。
あとはブラウザで

#### localhost:8000

を入力すると、WordPress のインストール画面が表示されます。

## ログを見る時

```
docker-compose logs -f tail 10
```

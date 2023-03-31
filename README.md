# これは何ですか
Ajaxのトレーニングで利用する簡単なAPIサーバーです。

# 起動方法

## yarnの場合

```
$ yarn install
$ yarn start
```

## npmの場合
```
$ npm install
$ npm start
```

and open http://localhost:8888

# エンドポイント

| HTTPメソッド | パス | 目的 |レスポンス例 | 
| -------- | ------------------------------- | ------------------------------ | ------------------------------ | 
| GET      | /api/todos | 現在のTODO情報全部を取得する | [{“id”: 1, “text”: “task1”, “done”: false }, {“id”: 2, “text”: “task2”, “done”: false }, {“id”: 3, “text”: “task3”, “done”: false }] | 
| POST     | /api/todos | 新たなTODOを作成する | {“id”: `新たに付与されたID`, “text”: `ポストしたテキスト`, “done”: false }} |                                                       |


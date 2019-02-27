# MyMarkdown

## 開発環境
### 初回立ち上げ
``` bash
# OSXにて
$ git clone git@github.com:prgyukke/MyMarkdown.git
$ cd MyMarkdown/
$ docker-compose up -d --build

# appコンテナに入る
$ docker-compose exec app /bin/bash
# npm install
```

### 2回目以降の立ち上げ
``` bash
$ docker-compose up -d
```

### appコンテナ(node v8.11.2)に入る
``` bash
$ docker-compose exec app /bin/bash
```

### ビルトインサーバ立ち上げ(localhost:8080)
``` bash
# npm run dev
```

### プロダクション用のビルド
``` bash
# npm run build
```

### appコンテナから抜ける
``` bash
# appコンテナ上にて
# exit
```
# MyMarkdown

## 開発環境
### 初回立ち上げ
```
# OSXにて
$ git clone git@github.com:prgyukke/MyMarkdown.git
$ cd MyMarkdown/
$ docker-compose up -d --build
```

### 2回目以降の立ち上げ
```
$ docker-compose up -d
```

### appコンテナ(node v8.11.2)に入る
```
$ docker-compose exec app /bin/bash
```

### appコンテナから抜ける
```
# appコンテナ上にて
# exit
```
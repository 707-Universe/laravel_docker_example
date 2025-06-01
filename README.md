# laravel_docker_example

---

## Dockerの起動方法

```
docker-compose -f .dev/docker-compose.yml up --build
```

上記のコマンドを実行する。

## envファイルを切り替えたい場合

### Developmentの環境変数で上書きする

```
cat .env.development > .env
```

#### 上書きをする前にバックアップをする場合

```
cat .env > .env.backup
```

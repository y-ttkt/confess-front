## confess-front

confessのフロントリポジトリです。

## 環境

- React 18.3.5
- TypeScript 4.9.5

## 環境構築

下記の流れに従って、環境構築を行なってください。

#### clone

```
git clone git@github.com:y-ttkt/confess-front.git
```

#### build
```
docker compose build
```

#### コンテナ作成
```
docker compose up -d
```

#### Laravelコンテナへの接続
```
docker compose exec -it confess-node bin/bash
```

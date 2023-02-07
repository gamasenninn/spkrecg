# spkrecg
Speaker recognition 

# tips

## Dockerの起動 
最初にビルドする場合は
```
docker docker compose up -d --build
```

すでにDocker Imageがビルドされている場合は、
```
docker docker compose up -d
```

## コンテナへ接続する(bash)
```
docker compose exec python3 bash
```

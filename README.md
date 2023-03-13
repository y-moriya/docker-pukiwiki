# pukiwiki

## Description

[PukiWiki Unicode版](https://pukiwiki.osdn.jp/)をalpineとh2oで構成したものの fork

## インストール

```shell
mkdir $HOME/pukiwiki
docker run --name pukiwiki -p 8080:80 -v C:\Users\wellk\project\docker-pukiwiki\pukiwiki:/ext -d pengo/pukiwiki
open http://localhost:8080
```

ディレクトリに既にデータがあるときは上書きしない。

## 2回目以降の実行

```shell
docker start pukiwiki
```

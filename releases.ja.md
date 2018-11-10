# Bootstrapの生成方法

## linux
```bash
cd .bitzeny/blocks
ls -1 blk[0-9]*.dat | sort | xargs cat > bootstrap.dat
```

## Windows
```bash
cd %appdata%\BitZeny\blocks
COPY /b blk00001.dat+blk00002.dat+blk00003.dat+blk00004.dat bootstrap.dat
```

## リリース

1. `bootstrap.dat`を`tar.gz`、`7z`に圧縮
2. `new release`より作成、作成したbootstrapをアップロード
3. 説明文に下記添付
    1. 作成者
    2. 作成日時
    3. チェックサム(sha256等)
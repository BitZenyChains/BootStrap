# BitZeny's Bootstrap

## 使い方

1. Walletを停止させます
2. `wallet.dat`のバックアップをします(安全な場所に保管してください。USBメモリ等)
3. `.bitzeny`(BitZenyのデータディレクトリ)以下の`blocks`,`chainstate`,`database`,`hashes`を削除します
4. [releases](https://github.com/BitZenyChains/BootStrap/releases)より最新の`bootstrap.dat.tar.gz`をダウンロードします
5. 7-zip等を使い展開し、`bootstrap.dat`を`.bitzeny`(BitZenyのデータディレクトリ)の直下に配置します
6. Walletを起動します
7. Headerの同期後(かなり遅いです)、bootstrap.datが読み込み終わるまでコーヒでも飲んで待ちましょう
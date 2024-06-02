# hello_cargo

このプロジェクトは「The Rust Programming Language 日本語版」の事始めの内容をまとめたものです。  
[The Rust Programming Language 日本語版 - 1. 事始め](https://doc.rust-jp.rs/book-ja/ch01-00-getting-started.html)

## インストール

このプロジェクトを使用するには、RustとCargoが必要です。もしまだRustをインストールしていない場合は、[こちら](https://www.rust-lang.org/tools/install)の手順に従ってインストールしてください。  

Rustがインストールされたら、リポジトリをクローンします：  

```bash
git clone https://github.com/eyamagishi/hello_cargo.git
cd hello_cargo
```

そして、Cargoを使ってプロジェクトをビルドします：  
```bash
cargo build
```

## 具体的なコマンドライン
```bash
cargo new   #プロジェクトを作成できる
cargo build #プロジェクトをビルドできる
cargo run   #プロジェクトのビルドと実行を1ステップで行える
cargo check #バイナリを生成せずにプロジェクトをビルドして、エラーがないか確認できる
```

## 貢献方法
このプロジェクトに貢献したい場合は、以下の手順に従ってください：  

1. リポジトリをフォークする
2. 新しいブランチを作成する (git checkout -b feature)
3. 変更を加える
4. 変更をコミットする (git commit -am '新しい機能を追加')
5. ブランチをプッシュする (git push origin feature)
6. 新しいプルリクエストを作成する

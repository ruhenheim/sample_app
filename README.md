# Ruby on Rails チュートリアルのサンプルアプリケーション

これは、次の教材で作られたサンプルアプリケーションです。  
[*Ruby on Rails チュートリアル*](https://railstutorial.jp/)  [Michael Hartl](https://www.michaelhartl.com/) 著

## ライセンス

[Ruby on Rails チュートリアル](https://www.michaelhartl.com/)内にあるソースコードはMITライセンスとBeerwareライセンスのもとで公開されています。詳細は [LICENSE.md](LICENSE.md) をご覧ください。  

## 使い方

このアプリケーションを動かす場合は、まずはリポジトリを手元にクローンしてください。  
その後、次のコマンドで必要になる RubyGems をインストールします。  

```
$ bundle install --without production
```

その後、データベースへのマイグレーションを実行します。  

```
$ rails db:migrate
```

最後に、テストを実行してうまく動いているかどうか確認してください。  

```
$ rails test
```

テストが無事に通ったら、Railsサーバを立ち上げる準備が整っているはずです。  

```
$ rails server
```

詳しくは、 [*Ruby on Rails チュートリアル*](https://railstutorial.jp/) を参考にしてください。

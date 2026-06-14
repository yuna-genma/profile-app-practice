# profile-app-practice

## 概要

COACHTECH 教材 Tutorial 9-1「Laravel基礎ハンズオン」で作成した成果物です。
自己紹介ページを作成しました。

## 使用技術

- PHP 8.x
- Laravel 10.x
- Blade テンプレート

## 学んだこと

- ルーティング → コントローラー → ビューの連携
- ルーティングの定義の仕方
- コントローラーの実装の仕方
- 模範解答と見比べて、自分のコードはコントローラーで`$name`,`$age`,`$hobbies`と変数を一つ一つ設定したが、`$data = ['name' => '山田太郎','age'=>25,...]`と`$deta`にまとめてデータを設定すれば、`return view()`で変数を渡すときも`$data`のみでいいのでコードが簡潔になると思った。

## 動作確認

`http://localhost/profile`にアクセスする

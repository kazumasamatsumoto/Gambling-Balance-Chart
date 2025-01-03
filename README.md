# Gambling-Balance-Chart

## 本アプリの目的

ギャンブルのスーパーアプリを作りたい。

収支表や台の紹介や、熱いポイントなど探すのに時間がかかっている

また収支表などなんか使いにくい感じがあるので、これをスタートアップみたいないきったデザインのアプリにすれば

なんか仕事している感が出せるのでは？という仮説検証のためのアプリ

## 技術スタック

フロント：React系（Nest.js）

バックエンド：TypeScript系（Nest.js）

バックエンド２：Go

バックエンド３：Rust

## 技術的に実現したいこと

マイクロサービスアーキテクチャや各種言語による違いの特性を理解しつつ進めていく

基本的には、一つの機能で3つの言語で実装して検証していく。

## 絶対に実装したい内容

・おしゃれな期待値と実収支の比較アプリ

・収支表を複式簿記のように表現することでいろいろ分析項目を実施

・マイクロサービス化によるいろいろなアプリとの連携ができるようにしたい

・パチンコの場合は、カメラを撮影したら想定回転率を算出できる機能は作りたい

## 利用料金

無料の想定

ユーザー数が増えて料金が遊びの範囲を超えた場合、有料化。

イベントの掲載や過去のデータからAIがどの台に設定が入りやすい、釘を開くのか？など分析ができるようにしたい。

## マイルストーン

フェーズ１：個人記録アプリ

・収支表

・期待値計算機能

・稼働期待値と実測値

・画像投稿機能

フェーズ２：SNSアプリ

・パチンコスロット専用SNS

・イベントに参加した結果個人結果としてどうだったか

・パチンコ店スタンプラリー機能

・パチンコ店周辺のおいしいお店機能

フェーズ３：AI機能搭載

・過去の出玉からイベント日にどの台に設定が入るか？を分析できるようにする

・パチンコ台をカメラで撮影すると回転数予測をおこなうAIを作成する

フェーズ４：ほかのギャンブル

・基本的にパチンコスロットがすきなので、ほかのギャンブルに対してはあまり食指が動かないので、作り切ったらにする。

## クラウドサービス

・AWSを使用して作成する

・CDK for Terraformを使用して管理する


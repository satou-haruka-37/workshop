# シナリオ

## 用語集

はじめにこのワークショップで使う用語を説明します。

  * 進行役：ワークショップを進行する役割の人（すでにOSSの開発に参加している人）
    * 1人
  * ビギナー：OSSの開発に参加したいけどまだ参加したことがない人・参加したことはあるけどまだ自信がない人
    * 複数人
  * メンター：ビギナーをサポートする役割の人（すでにOSSの開発に参加している人）
    * 複数人

## 目的

「OSS Gateワークショップ（チュートリアル）」の目的は「OSS開発に参加する最初の一歩を支援すること」です。

## 対象

  * OSSの開発に参加したいけどまだ参加したことがない人
  * OSSの開発に参加したことはあるけどまだ自信がない人

## 目的の実現方法

OSSの開発に参加したいけどまだ参加したことがない人が参加していない理由は「漠然とした不安がある」からです。このワークショップでは「不安」を解消することによりOSS開発に参加する最初の一歩を支援します。

「不安」の原因は次の通りです。

  * 「やり方」を知らないから
  * やったことがないから
  * 「失敗が怖い」から

これらの「不安」の原因を解決するために次のことを実施します。

  * 「やり方」を伝える
  * 「やり方」を実際にやってみる
  * やるときは「失敗」しても大丈夫な状況でやる

具体的には次の方法を実施して「不安」を取りのぞきます。

  * オススメのOSS開発参加方法を紹介
  * オススメの方法を実践
  * 対象OSSはメンターが開発に関わっているOSS

OSSの開発に参加する方法は無数にありますが、「好きなようにやっていいんだよ」と言うと不安を増す原因になってしまいます。「好きなように」と言われてもそもそもどのような「やり方」を選べるかもわからないからです。

このワークショップでは、OSS Gateがオススメする方法を「1つだけ」説明し、実際にビギナーが「やってみます」。あえて1つに限定することにより迷いポイントが減り、不安を軽減できるからです。

ビギナーがオススメの方法を試すとき、「こんなissueを立てて嫌がられないかな…」と「不安」にならないよう、開発対象のOSSはメンターが開発に関わっているOSSにします。メンターからその場で「それをやっても大丈夫だよ、やってみよう！」と言ってもらえたら、その「不安」を取りのぞけるからです。

## 目的達成の評価方法

ワークショップ後、自分1人でもOSSの開発に参加できる「気がするか」どうかを判断基準とします。「気がする」なら、OSS開発への心理的敷居は十分に下がっていて、OSS開発参加への具体的なとっかかり方法が身についた、と判断します。

## 大事にしたいこと

ビギナー：

  * 実際にやってみる！（経験すれば多くの不安は解消するはず！）
  * 楽しむ！（経験すれば楽しいことがわかるはず！）

メンターの人の動き方の方針：

  * 答えを教えない（開発に使う言語・開発対象のOSSが多様なので知らないことも多いはず）
    * 代わりに一緒にやる。自分のPCでも並行して作業してわかったら教える、ではなく、ビギナーのPCで一緒に作業ということ。そのとき、自分がどうして次にこう行動をしようとしているのかの理由を伝えながら一緒に作業する。
  * 自分ならこういうときにどう考えてどう行動するかを伝える
  * 自分がフィードバックを受ける側ならこう受け取る、ということを伝える

## 開始前

  * ビギナーはネットワークの設定をすること
  * メンターはネットワークの設定をすること

## 10:30 オリエンテーション

目的：

  * ビギナーがどうやってOSS開発に着手すればよいかわかること

今日の進め方を説明：

  * 進行役はスライドを使って↓に書いているやり方を説明する。（スライドはoverview/または↓を参照。）
    * [スライド on Rabbit Slide Show](http://slide.rabbit-shocker.org/authors/kou/oss-gate-workshop-tutorial-overview/)
    * [スライド on SlideShare](http://www.slideshare.net/kou/oss-gate-workshop-tutorial-overview)


* 進行役とメンターはビギナーと話してビギナーが開発対象とするOSSを決める
    * 次のことを加味しながら決める。OSSの技術的な難易度はそれほど重視しなくてよい。
      * ビギナーが使っているOSSにする
      * ビギナーが困っているOSSにする（インストールがうまくいかないとか）
      * メンターが開発に関わっているOSSにする

## 10:40 アイスブレイク

  * ビギナー・メンターそれぞれ同じテーブルの人たちに自分がどうしてOSS Gateに関わっているかを話す
  * メンターはビギナーと話してビギナーが開発対象とするOSSを決める
    * 次のことを加味しながら決める。OSSの技術的な難易度はそれほど重視しなくてよい。
      * ビギナーが使っているOSSにする
      * ビギナーが困っているOSSにする（インストールがうまくいかないとか）
      * メンターが開発に関わっているOSSにする
  * [作業ログissueテンプレート](https://github.com/oss-gate/workshop/issues/4)を元に自分用の作業ログissueを作る

## 10:50 OSS開発手順を説明
  * 一通りの流れがわかる
    * 頭でわかる（知識としてわかる）

やること：

  * 一通りの流れを説明する

## 11:00 開発対象OSSを動かす

目的：

  * OSS開発に着手したときに最初にやるべき「動かすこと」を実際にやる

目的達成のために達成したいこと：

  * 困ったら相談するという習慣を身につけて欲しい
    * 実際はリモートで相談することになるが、まずは隣同士、グループ内で相談できるようになる
  * 動かすことに集中する
    * 他のことに手を出したくなるかもしれないけど、まず動かすことが大事、ということを覚えてもらう
  * ドキュメントに不備があるときに、文句を言う（Twitterでアピールするとか）よりも、次にドキュメントを読んだ人が困らないように直しておこう、と考える習慣を身につけてもらう
    * 文句を言うことはスゴイことでもカッコイイことでもない！文句を言っている時間を使って直そう。

やること：

  * ドキュメント（READMEなど）に書いている通りにインストールしてみる
    * ドキュメントにtypoや古い記述など不備があったら作業ログissueにメモしておく。理由は後でpull requestするから。
    * インストール方法や使い方をググる前に公式ドキュメントを参照する習慣をつける。
      * ググって見つかる非公式の情報がないと使えないOSSよりも公式ドキュメントを読めばわかるOSSにするべきで、そうなっていないなら私たちが開発に参加してよいものにするべき。
  * インストールできたらドキュメントに書いている通りに動作を確認する

## 12:00 ミニふりかえり

目的：

  * ふりかえりのリハーサル
    * 作業ログが後で自分の役に立つことを実感してもらう
  * 今後進むべき方向を確認して、午後を有意義に過ごすため

目的のために達成したいこと：

  * 「まず動かす」のときに作業ログをとる

やること：

  * メンターの人数よりビギナーの人数が多い場合
    * 1メンターあたりn人のビギナーをフォローする
    * 1人のビギナーがふりかえりをしている間、別のビギナーはなにか得られるものがないかという気持ちで見守る
    * 1人終わったら別のビギナーと交代
  * ふりかえりの仕方はissueに書いてある

## 12:15 （昼食）

近所にランチを食べに行きましょう。

ビギナーは午前中に気になったことを進行役・メンターに聞いてみてください。

進行役・メンターはビギナーに楽しんでいるか聞いてみてください。

## 13:15 プロジェクトにフィードバックする

目的：

  * 「動かす」を実際にやってみて気づいたことをOSSプロジェクトにフィードバックすることを「体験」する
    * issueでもpull requestでもよい

目的達成のために達成したいこと：

  * 進行役はスライドを使って↓に書いているやり方を説明する。（スライドはfeedback/または↓を参照。）
    * [スライド on Rabbit Slide Show](http://slide.rabbit-shocker.org/authors/kou/oss-gate-workshop-tutorial-feedback/)
    * [スライド on SlideShare](http://www.slideshare.net/kou/oss-gate-workshop-tutorial-feedback)

やること：

  * 「動かす」のなかで見つけたドキュメントの不備がどんなものか他の人に伝わるようにまとめる
    * わかりにくかったところに対する改善案をまとめるのもよい。
  * まずは自分の考えを整理する
    * OSSの開発ではインターネット越しのやりとりが基本なので、文章で伝える必要がある。
    * 少なくとも自分が理解できるような文章にまとめること。
    * 自分の考えを文章にまとめるのは難しいと思うのでメンターには考えの整理を手伝ってあげて欲しい。
    * まとめたものは作業ログissueにコメント。
  * 自分の考えがまとまったら開発者に伝わるようにまとめ直す
    * 「読む人」が理解できることが大事
    * このように報告してほしいとまとめているOSSもある。たとえば、GitHubを使っているOSSは`CONTRIBUTING.md`を使っていることがある。
    * メンターは読む人視点を伝えてあげて欲しい。
    * これもまとめたものは作業ログissueにコメント。
  * 実際に報告する
    * これはupstream（開発元）のissueに報告。

## 14:50 休憩

10分休憩。

## 15:00 プロジェクトにフィードバックする（続き）

## 15:50 休憩

10分休憩。

## 16:00 ふりかえり

目的：

  * ビギナーのよい行動を伸ばすため
  * ビギナーが困っていることを解決するため
  * ビギナーが見過ごしている問題（= 解決するべき問題）を気づかせるため
  * ビギナーが明日進むべき先を目指すため

目的達成のために達成したいこと：

  * ビギナーの作業ログを元にメンターがビギナーをサポートする。

やること：

  * メンターの人数よりビギナーの人数が多い場合
    * 1メンターあたりn人のビギナーをフォローする
    * 1人のビギナーがふりかえりをしている間、別のビギナーはなにか得られるものがないかという気持ちで見守る
    * 1人終わったら別のビギナーと交代
  * ふりかえりの仕方はissueに書いてある

## 16:15 まとめ

目的：

  * 今日やったことの意味を再確認する
  * 今日やったことを明日以降に活かす

目的達成のために達成したいこと：

  * 進行役はスライドを使って↓に書いているやり方を説明する。（スライドはconclusion/または↓を参照。）
    * [スライド on Rabbit Slide Show](http://slide.rabbit-shocker.org/authors/kou/oss-gate-workshop-tutorial-conclusion/)
    * [スライド on SlideShare](http://www.slideshare.net/kou/oss-gate-workshop-tutorial-conclusion)

やること：

  * 今日やったことを再確認
  * 今日やったやりかたの思惑を説明
  * 明日からのヒントを提示

## 16:30 アンケート記入

  * アンケートを記入する
    * [ビギナー向けアンケート](https://docs.google.com/forms/d/1jSJl_LEWTaoL8pxS_c3lVCAuWJ5CC4nrbbBSuNiXYqw/viewform)
    * [メンター向けアンケート](https://docs.google.com/forms/d/1y5vtc46yo1SXHHgR4LHBmEAxsyeTLskci_a-PQaB7Pg/viewform)
  * このアンケートはこのあとの「ワークショップのふりかえり」ですぐに使う

## 16:45 ワークショップのふりかえり

  * アンケート結果をみながら今後もっとうまくやるにはどうすればよいかを検討する
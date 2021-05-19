# Post Map 
URL:


- 投稿した記事
![Readme3.png](./Readme3.png)


- 投稿一覧
![Readme2.png](./Readme2.png)


- マインドマップ作成
![Readme1.png](./Readme1.png)

## アプリについて(概要)
「Post Map」は、Mindmapアプリの一つです。
目標達成、思考整理等のためにお使いください。


そこで、お願いがあります。  


あなたの
- 目標達成のために活用したマインドマップ
- 成功を可視化したマインドマップ  


を他の方にも共有していただけませんか？  


同じ目標を持った人の助けになります。  


マインドマップ + 投稿　＝　「Post Map」  


他人の意見を参考にし、最速で理想の自分を実現しましょう！

## なぜ、このアプリを作ったのか？
YoutubeやGoogle検索、SNSを観察している中で、ある一つの発見がありました。
それは、成功する方法はもちろん「成功者になるまでのプロセスに需要があること」に気がつきました。
現に、Youtubeの再生数を見た時、「モーニングルーティーン」「現在までの経験談」など
が伸びています。つまり、成功者のプロセスや、生き方に興味があり、よりRealを追求していることがわかりました。
ただ、それは具体性が欠けていて、抽象的なものになっています。
そこで、具体的かつ、見やすいマインドマップを選択しました。
普段は、普通にマインドマップを活用していただき、目標達成できた時、投稿していただければ、詳細な意見を、同じ目標を持った人にリーチできる思ったからです。
また、投稿時に意見をもらえるコメント機能がついているので、より前向きなものになっています。

## 使用技術
- Ruby 2.7.2 Rails 6.1.3
- Nuxt(Vue.js)
- Vuetify
- Docker/docker-compose
- Nginx, Unicorn(sockets通信)
- Git, GitHub
- Rubocop
- AWS (VPC, EC2, Route53)

## 機能一覧
### rails
- ログイン機能(devise token auth)
- 画像投稿機能(carrierwave)
- CRUD機能
- ページネーション機能(kaminari)
- いいね機能
- タグ機能
- コメント機能(Websocket)
- フォロー機能
- 通知機能(Websocket)
- 検索機能
- テストデータ投入(faker/gimei)
- API化(rack-cors)
- 構文規約チェックツール(rubocop)

## 開発において意識した事
- レスポンスの高速化。
- 無駄な思考をしないよう、シンプルかつ色の統一を意識しました。
- しっかり現状把握を行い、需要があり、被りがないものを作ろうと努めました。

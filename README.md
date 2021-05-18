# Post Map
【ポートフォリオ】成功者の地図が見れるWebアプリ「Post Map」

## 概要
あなたが、目標達成のために活用した、マインドマップを他の方にも共有していただけませんか？
同じ目標を持った人の助けになります。
他人の意見を参考にし、最速で理想の自分を実現しよう！

## なぜ、このアプリを作ったのか？
YoutubeやGogle検索、SNSを観察している中で、ある一つのことに気付きました。
それは、「成功する方法だけでなく、成功者になるまでのプロセスに需要があること」です。
現に、Youtubeの再生数を見た時、「モーニングルーティーン」「学生時代の話」など
が伸びています。つまり、成功者のプロセスや、生き方に興味がある人がいるようです。
ただ、それは具体的には、語られてなく抽象的なものになっています。
そこで、詳細かつ分かりやすく、説明できるように作成したのが「Post Map」です。

## 使用技術
・Ruby 2.7.2
・Ruby on Rails 6.1.3
・Nuxt(Vue.js)
・Vuetify
・Docker/docker-compose
・Nginx, Unicorn(sockets通信)
・Git, GitHub
・Rubocop
・AWS (EC2)

## 機能一覧
rails
・ログイン機能(devise token auth)
・画像投稿機能(carrierwave)
・CRUD機能
・ページネーション機能(kaminari)
・いいね機能
・コメント機能(Websocket)
・フォロー機能
・通知機能(Websocket)
・検索機能
・テストデータ投入(faker/gimei)
・API化(rack-cors)
・構文規約チェックツール(rubocop)

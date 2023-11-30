# kadai05_API

「kadai05_API」の課題用リポジトリ

- 数回に渡る社員との面談内容を元に、社員の性格やスキル傾向分析、社員に必要なサポート提案、向いている職種などを提案してくれます

## DEMO

https://chat.openai.com/g/g-braEVMD6C-data-insight-explorer
※全体非公開のGPTs
https://73.gigafile.nu/1205-o5b13cfcb53fffb6de74d0a4bc4eb75a3
※DEMO動画 12/5まで有効


## 紹介と使い方

- 顧客名をメッセージに入れるだけで、これまでの面談内容を全て分析し性格やスキルの傾向をまとめてくれます
- 次に上記結果を元に次のプロンプトが走るようスプレッドシートに指示が入っているので、分析結果を元にどんなサポートができるか提案してくれます
- 次に、対象者に向いている職種やポジションの提案までしてくれます 指示書はこちら https://docs.google.com/spreadsheets/d/17EGfu4rrhRyttD2BaZWuQbWVxZnY6GRR2zboQeHbAGk/edit#gid=0 ※これ以上増やすとエラーが頻発するため3行で様子見

## 工夫した点
 - gpts actionのapiでスプレッドシートに連携させました
 - 登録されたデータを読み込ませるだけでなく、対象者の性格傾向や社員に対するフォロー提案までできるようプロンプトの流れを作成しました
  
## 苦戦した点
- 実はこの課題に至るまでに色々なAPIを試しては挫折、試しては挫折しました。MAPとwebカメラを連動させてアプリを作りたくて、WindyのAPIキーを取得したり、Google GeocodingのAPIも取得してみました。が、タイムアウトで別案を考えたのが今回の課題となります。
参考にしたページ：https://qiita.com/team_kuchibashi/items/bd58ab800067ae8e9664


## 参考にした web サイトなど

https://qiita.com/iconss/items/3db0761bb4cfe1422a6e

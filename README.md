# マッチングアプリマスター
モテ男（マッチングアプリマスター）への道標となる マッチングアプリ完全攻略サービスです。<br>
<br>
<img width="1439" alt="スクリーンショット 2021-10-22 23 47 48" src="https://user-images.githubusercontent.com/72130011/138480186-cc0a181c-c1a0-468c-a278-7286b921b45d.png">

# アプリURL(対応端末: iPhone X 以降(スマホ))
LIFFアプリ(LINEで動くWebアプリ)なのですが、外部ブラウザ(SafariやChrome)からも開くことが出来ます。<br>
※ 二極化<br>
<br>
https://dating-apps-master.com/top<br>
<br>
🌷 PV数 <br>
<br>
🌷 友だち登録数15人 (2021年10月22日現在)

# サービス概要
マッチングアプリを利用しているが女性と上手くいかない、女性の扱い方がわからない、女性との出会いが無くて困っている人に<br>
目的別に適したマッチングアプリを導き出し、そのアプリごとのテクニックやコツを全て指南して、モテ男（マッチングアプリマスター）への道標となる<br>
マッチングアプリ完全攻略サービスです。

# 登場人物
- マッチングアプリを利用している男性
- マッチングアプリマスター（モテ男）になりたい男性
- 女性との出会いが欲しい男性

# ユーザーが抱える課題
- マッチングアプリを利用しているが女性と上手くいかない、進展できない。
- 女性との出会いが無く、女性のことがよく分からない。女性の前だと緊張して余裕が持てない。
- ネット等に情報は掲載されているが、アフィリエイトなどが多い為、あまり参考にならない場合がある。
- また、参考になるサイトがあったとしても各サイトによって、書かれている内容が違い、どの方法が一番良いのか分からない。
- 具体的にどのようなアクション、デートスポットに行けば良いのか一連の流れが分からない。
- モテ男になりたい。

# 解決方法
その男性の目的別に適したマッチングアプリを導き出し（「適正アプリ診断」）、そのアプリごとのテクニックやコツを最初から最後まで（「プロフィール設定」〜「実際に女性と会って解散するまで」）全て指南して、ゲーム要素も含めて楽しみながらモテ男（マッチングアプリマスター）へと変貌させる。

# プロダクト
モテ男（マッチングアプリマスター）への道標となる、マッチングアプリ完全攻略アプリケーション

# 機能
- 「適正アプリ診断」
  - ユーザーに適したアプリを導き出す。
- 各「マッチングアプリ(攻略アプリ)の特徴・説明」
- 目的別の「攻略の流れ・ステップ」
  - <1.プロフィール設定> 〜 <8.デート当日(デート別)>
- 目的別の「おすすめデートプラン一覧」
  - 各デートプランの具体的な <詳細情報>・<アクション> も記載されている。
- 各女性ごとの「好感度」・「進展度」を可視化する。
  - <デート回数>・<デート結果>を元に算出。
- 各女性ごとの「おすすめの次回デートプラン・日程」を算出する。
  - <モテ度>・<デート結果>・<日付> を元に算出。
- 自分の「モテ度」を可視化する。
  - <デート回数>・<好感度>・<進展度> を元に算出。
- 「デートの予定を登録」すると、LINE通知が来る。(各女性詳細ページからデート登録出来る。)
  - <女性の名前>・<デート日程>・<デートプラン>・<そのデートプラン情報のURL> が記載されている。

# マーケット
10代〜20代のモテたい男性（おそらく全世界のほとんどの男性）

# 画面遷移図
https://xd.adobe.com/view/ce7f700b-05d8-4316-8a0f-fdc8f4261687-9b2c/
修正する？

# ER図
<img width="879" alt="スクリーンショット 2021-10-23 0 23 28" src="https://user-images.githubusercontent.com/72130011/138481436-b58d1470-382e-4bd4-b5e6-aeaa213dd98e.png">

# インフラ構成図
![インフラ構成図](https://user-images.githubusercontent.com/72130011/138585363-58d128e8-ce16-4c11-8c09-912a2b9a8932.png)

# 使用技術
- Ruby 3.0.2
- Rails 6.0.4
- JavaScript
- LIFF(LINE Front-end Framework)
- LINE Messaging API
- MYSQL
- Nginx
- Unicorn
- AWS
  - VPC
  - EC2
  - RDS
  - ALB
  - Route53
  - ACM
- RSpec

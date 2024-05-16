# セグメント　- レクチャーと練習問題で極めるGA4レポート（標準レポート・探索レポート・セグメント）
https://support.google.com/analytics/answer/9356048?hl=ja&sjid=13238539530676159184-AP
## ユーザーセグメント
・セグメント: 一部抽出。除外はしていない
・フィルタ: 作成したレポートに対して絞り込む。データの除外を行う
※セグメントとディメンションの違いについて要、要約
セグメント→ディメンション→指標の順で設定する
### よく使うイベント
訪問: first_visit session_start
ページ利用: page_view scroll view_search_results
cv: purchase
パラメータとして、page_location page_title ga_session_number search_term item_nameなどを組み合わせて使う
BIgQueryではvideo_startを使う
###　ディメンション化されたパラメータ
#### イベント(パラメータ)
video_start/video_progress/video_complete(video_title video_url video_provider)
click(link_url linl_domain)
file_download(file_name file_extention)
view_search_results(search_term)

### シーケンスを利用したユーザーセグメント
シーケンス(*)を利用すると、ユーザーがサイトを利用した順序に基づくユーザーセグメントを作成できる。

## セッションセグメント
含める、除外するの条件をセッションに対して適用するセグメント。
条件グループについては、
・グループを複数作って条件を1つにする
・単一のグループで複数条件
どちらでも同じ結果になる。
## イベントセグメント
含める、除外するの条件をイベントに対して適用するセグメント。
GA4で追加された。
## 予測指標セグメント
パーセンタイルについて: 機械学習の予測で、内部的に一人一人のユーザーの「今後７日間の購入の可能性」を求めている。
ユーザーを可能性の値の低い順に並べたとき、X%のところにいるユーザーの可能性のこと。
https://support.google.com/analytics/answer/9846734?hl=ja 予測指標について

## おすすめのセグメント
・全般
・テンプレート
から、Google側が設定してくれている
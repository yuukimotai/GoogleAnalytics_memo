# ユーザー軸1
### ♢ユーザーの合計数
全ユニークユーザー数の事
### ♢ユーザー
対象サイトに1秒以上滞在したユニークユーザー数
### ♢新しいユーザー
新規に訪問したユニークユーザー数
### ♢ユニークユーザーのスクロール数
対象ページを90％以上スクロールしたユニークユーザー数

# ユーザー軸2
### ■ エンゲージメントのあったセッション数(1ユーザーあたり)
10 秒以上継続するか、コンバージョン イベントが発生するか、ページビューまたはスクリーン ビューが 2 件以上発生したセッションの数。
エンゲージメント セッション数は、エンゲージメントの少ないセッションの数の逆数です。
### ■ 平均エンゲージメント時間
ウェブサイトがユーザーのブラウザで目的のコンテンツとして表示されている平均時間、またはアプリがユーザーのデバイスでフォアグラウンド表示されていた平均時間。
平均エンゲージメント時間 = ユーザー エンゲージメントの合計時間 ÷ アクティブ ユーザー数
### ■　ユーザーあたりのイベント数
総イベント数 / ユーザー
### ■ ユーザーあたりのビュー
表示回数(ページビュー数) / ユーザー

# セッション軸
###　♢セッション
ユーザーがサイトを表示した時に始まり、30分の不操作があると終了する。UAとはセッション終了の条件が変わり、GA4の方が少なくなる傾向。
### ♢エンゲージのあったセッション
以下の3つのいずれかを満たすと「エンゲージのあったセッション」と定義される。
1. 10秒以上のセッション
2. 2PV以上のセッション
3. CVのあったセッション
ただし、すべてのセッションが「エンゲージのあったセッション」ではないため、
セッション > エンゲージのあったセッション
### ■エンゲージメント率
エンゲージメントのあったセッションの割合。
エンゲージメント率 = エンゲージメント セッション数 ÷ 合計セッション数
エンゲージメント率は、直帰率の逆数です。
### ■セッションあたりのエンゲージメント時間
ユーザーエンゲージメント（ブラウザにフォーカスが当たっていた延時間）をセッションで割って求める割り算の指標
セッションあたりのエンゲージメント時間 = ユーザーエンゲージメント / セッション
### ■セッションあたりのイベント数
イベント数をセッションで割って求める割り算の指標。
セッションあたりのイベント数 ＝ イベント数 / セッション

# イベント軸
### イベント数 
発生したイベントの合計数。　イベントの種類は限定してないので注意
### 表示回数
page_view イベントの発生回数。ページビュー数と同義
### コンバージョン
コンバージョンとして定義したイベントの発生した回数
コンバージョンを複数定義している場合はすべて含まれる
### 合計収益
purchaseイベントと同時に送信された値(value)の合計値
### イベント収益
イベントと同時に送信された値(value)の合計値

# ディメンションの定義
https://support.google.com/analytics/answer/9143382?hl=ja#　を参照
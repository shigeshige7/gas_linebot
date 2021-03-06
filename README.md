# アプリケーション概要
アプリケーション名：電大バスBot<br>

大学のバスがあと何分で出発するかを教えてくれるLINEBotです。<br>
駅から大学に行く際や、大学から駅に行く際にワンタップで瞬時に残り時間を教えてくれるLINEBotです。<br>
大学へのアクセスは3つの駅があり、それぞれ異なる時刻でバスが運行しており、「駅から大学」と「大学から駅」の合計6パターンに対応した残り時間を返答してくれます。<br>
行き先パターン選択には、リッチメニューを導入し、ユーザーは行き先を入力ではなくワンタップで示すことができ、快適にBotを使用することができます。

## アプリケーション動作動画
https://user-images.githubusercontent.com/58199648/107315963-0fc6c900-6adb-11eb-8572-43bc833b0df0.mp4

# 機能一覧
* 行き先を選択し、出発時間までの残り時間が何分かを返答

# 使用技術一覧
* Google Apps Script(spreadsheetsURL：https://docs.google.com/spreadsheets/d/1Obm6Ra-Y_nhIB7hyy0rllbxHO--xK_nYTbX4m8RXKDM/edit?usp=sharing)
* LINE Messaging API
* Webhook<br>

# なぜ作ったのか？
大学の通学バスを利用していて、通学時や授業後に毎回のようにweb上にある時刻表を確認し、現在時刻との差分を計算して残り何分でバスが到着するかを調べなければわからないという課題があったから。この毎回行っている作業はもっと効率的にできると思ったのと、同様にこの課題を感じている学生はたくさんいると感じ開発を行った。

# 製作期間
約3週間ほど

# 作った感想
はじめて自分で開発したもので、実際に思い通りに動いてくれた時の楽しさが忘れられない。特に嬉しかったことが、友人に使ってみてと提案した際に「すごく便利でいいね！ありがとう！」と感謝を伝えられたことである。<br>
こだわった点では、全てのルートをワンタップで確認できるようにリッチメニューを導入したことと、バスが到着しているときには、到着していることに加え次のバスの到着まで示すことで、UI・UXの向上を図った。<br>
最初は、何も分からない状態でしたが、徐々に分かるようになり開発の楽しさや自分で作ったもので感謝されるやりがいなどを痛感しました。

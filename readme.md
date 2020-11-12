# じゃんけんテトリス
デプロイ先：https://dausuke.github.io/02_13_jankenTetris/

## 紹介
- パズルゲームとじゃんけんを組み合わせたようなゲームにしようと思い、作りました。
- テトリスのように上から落ちてくる相手の手にあわせて、自分の手を変更しじゃんけんをします。

## 工夫した点・こだわった点
- ゲーム要素を高めるため、制限時間とスコアを勝敗によって増減するようにしました。
- チープな雰囲気にしたかったので装飾加えず、色も極力使わないようにしました。

## 苦労した点
- 勝敗判定を行うための、衝突判定に4日間費やしました。。。
- ランダム生成される相手の手の位置情報が、最初に出てきた手の位置情報しか取得できず未解決です。
- 勝敗判定を行うタイミングが難しくかなりシビアなタイミングでの判定となってしまった。
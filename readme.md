# 人狼ゲーム(仮)

## DEMO

  - 

## 紹介と使い方

  - 嘘は下手ですが某人狼ゲームの内容が面白そうだったので作成に挑戦しました。
  - 内容はランダムに選出された人狼を当てずっぽうで選出する運ゲームです。

  - ゲーム画面内をクリックしてインデックスを進めていく。
  - 自分の投票パートでは誰に投票するか選択する。(インデックス2)
  - 最終的に一番多く投票された人が人狼かそうでないかをジャッジします。

  - ただのランダム関数でCPUは投票しているので村人・人狼に関わらず自分自身に投票してしまう...
  - 発言を加えたりや複数のプレイヤーでも遊べるようにするなど改良したい点はたくさんある。

## 工夫した点

  - 教えていただいたランダム関数を使いました。
  - 人狼の判断方法や投票結果を表現するのに変数で表現するのに苦労しました。

## 苦戦した点

  - switch()内のコードは常に実行され続けるのでi++やランダム関数を
    の実行を理想の回数で止めるために思考錯誤した
   

## 参考にした web サイトなど

  - https://www.wwsft.com/jsh5/jsh5_021.html
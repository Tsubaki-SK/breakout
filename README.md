# breakout
Breakout with python

![breakout_image](https://user-images.githubusercontent.com/61465092/75628875-6582c800-5c20-11ea-89ae-bc1a278eddbb.png)



# スタート方法
* Ctrlキーを入力したらBGMと共にゲームがスタート。
* スタート時、ボールはオレンジ色の線の方向に進む。


  
# シールド(自機)
* ボールがシールドと接触した場所で、その後のボールの飛ぶ方向が決まる。真ん中付近に当たった場合は真上に飛び、左側に当たった場合はボールも左側に飛ぶ。



# ブロック
* ブロックの色によって性質が異なる。

  - 緑色 : 普通のブロック
  - 水色 : シールドの横幅が最大になる。
  - 青色 : シールドの横幅が最小になる。
  - 白色 : 横幅がスタート時の大きさに戻る。
      


# ゲームオーバー
* 以下の場合、ゲームオーバーとなる。

  - シールドの赤い部分にボールが接触した場合
  - 一番下のオレンジの壁にボールが接触した場合


# ポイント
* ブロックひとつにつき10ポイントが与えられる。連続でブロックを破壊した場合、連続で破壊した個数×5ポイントが上乗せされる。
* ゲームをクリアした場合、クリアの早さに応じてボーナスポイントが与えられる。ただし、9分12秒以内(bgm2周分)にクリアしない場合、ボーナスポイントは0になる。



# 使用BGM,効果音のサイト
* ゲームクリア時のBGM
    <a href="https://pocket-se.info/">ポケットサウンド/効果音素材</a>

* その他の効果音、BGM
    <a href="https://maoudamashii.jokersounds.com/" title="フリー音楽素材/魔王魂" target="_blank">フリー音楽素材/魔王魂</a>

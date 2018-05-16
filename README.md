# mig(Multi-purpose Interactive Gadget)
## What's this?
私が普段使っているMacbookに外付けして使うガジェットです．  
RaspberryPi zero(OTGモード)と液晶を組み合わせたものを，Macに有線接続して使用します．  
GUIとして，KIOSKモード（デジタルサイネージ用の全画面表示モード）で立ち上げたブラウザ上で，Javascriptを走らせます．


## What's 'interactive'?
現在は，ガジェットにSSH接続して，データを流し込んで表示させるのが第一目標．それができたら，RaspberryPiのタッチパネル液晶を利用して，ガジェットへの操作をMacに反映することで，このガジェットを入力インタフェース化する(interactive化)ことに挑戦したい．

## Loadmap
- ~~RaspberryPiのセットアップ~~
- GUIのベースを作って時刻を表示
    - 画面上側1/5ほどが黒帯で利用不可になっているのを修正
    - Chromium-browserのRestore Pages?のダイアログがでないようにしたい
    - 時刻の同期に関する問題を解決する
- データ(ニュースなど)を流し込んで表示
- 入力インタフェース化

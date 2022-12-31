# mypkg
#### [![test](https://github.com/21c1041yukikumazawa/mypkg/actions/workflows/test.yml/badge.svg)](https://github.com/21c1041yukikumazawa/mypkg/actions/workflows/test.yml)
#### このリポジトリはros2のテストをするためのリポジトリです。　　
## このソフトウェアについて
#### パブリッシャーの*talker*とサブスクライバーの*listener*が通信する様子を再現する。
#### launchで`ros2 run`を実行するため`talker.py`と`listener.py`を同時に実行できる。
## インストール方法
#### *ros2*がインストールされているUbuntuにこのリポジトリのクローンを作る。
## 使い方
#### `ros2 run launch mypkg talk_listen.launch.py`を実行する。
#### talkerからの通信をlistenerが拾えていればros2が正常に動作していることがわかる。 
## 動作環境  
#### ros2がインストールされているUbuntu
## テスト環境
#### Ubuntu(22.04) 
## ライセンス   
#### 三条項BSDライセンスにより使用、再配布が許可されています。しかし、このソフトウェアの使用には保障はありません。
#### ©　2022 Yuki Kumazawa

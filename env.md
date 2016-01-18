# 環境構築について

- 参考) laravel リファレンス etc..

## 方法

Homesteadを使う


## 前提

- mac OS X 
- virtual boxはインストール済
- vagrantもインストール済


## 設定

1 vagrant box add laravel/homestead

2 git clone https://github.com/laravel/homestead.git Homestead

3 Homestead/ 以下にhomestead.yamlがあるからそれを環境に合わせて修正する。

自分はauthkeyとshared forderの設定をしただけで動いた。


4 vagrant up 

エラーが出たら都度修正



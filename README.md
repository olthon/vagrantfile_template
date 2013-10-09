(Test)

---
### 概要 ###

Vagrant vagrantfileの自分用テンプレートです



### Box ###
とりあえず本通りに。
```bash
$ vagrant box add centos64_gihyo https://dl.dropboxusercontent.com/u/3657281/centos64_ja.box
```

### 余談 ###
vagrantのHomeには各種設定の他に、addしたboxも入るため、SSDで容量が心配なのでHomeをHDDの方へ移動させてます。

* Mac
```bash
$ echo 'export VAGRANT_HOME=[パス]' >>~/.bashrc
```
* Win  
環境変数 VAGRANT_HOME にパス記述

デフォルトは

* Mac : /Users/hogehoge/.vagrant.d
* Win : C:\Documents and Settings/hogehoge/.vagrant.d


### 参考 ###
* [Vagrantをはじめてみたい方へ「Vagrant入門ガイド」を書きました - Shin x blog](http://www.1x1.jp/blog/2013/09/vagrant_beginners_guide.html)
* [Vagrantのboxなどが格納されるディレクトリを変更する - Qiita [キータ]](http://qiita.com/yando/items/679dbfba244924320ea0)

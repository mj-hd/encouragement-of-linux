# Linuxのすゝめ
宇大情報工学科3年生(本当は4年生のはず)  
![Twitter](images/twitter_profile.png)  
Twitter: [@mjhd_devlion](https://twitter.com/mjhd_devlion/)  
Web: [http://devlion.net](http://devlion.net)

---

# 自己紹介
* プログラミングが好き
* 最近はWebデザインをよくやっている

---

# こんなのつくりました

[新電力バンク](https://www.shindenryoku.pw)  
![](images/shindenryoku.png)



# HSP部屋

[HSP部屋](http://hsproom.me)  
![](images/hsproom.png)



# ASC
* Simulator&Assembler

![](images/asc.png)

---

# 本題

---

# Linuxを入れましょう

![Linux Penguin](images/linux.jpg)



* Windows, Macintoshと同じ、OSの一つ
* 世界のサーバ用OSのシェア一位

![](images/server_share.png)

[進む大企業のLinux導入--Windowsのシェアは減少](http://japan.zdnet.com/article/35057416/)より



# 特にWeb関連はLinuxの知識が必要

---

# ディストリビューション
* Linuxにはディストリビューションと呼ばれるパッケージが沢山ある
* Ubuntu, Fedora, CentOSなど沢山ある

---

# ArchLinux
![](images/arch-linux.png)

---

# メリット
* 勉強になる
* 日本語のWikiがかなり充実
* パッケージ数が尋常じゃない(ソフトを楽にインストールできる)

---

# GUI環境
* XServer
* DisplayManager
* WindowManager
を入れればWindowsみたいに使える



# DisplayManager
* LightDMがおすすめ
* 正直なんでもいい気がする

![](images/overview.png)

---

# CUI環境



# XMonad
* タイル型WM
* Haskellで設定ファイルを書く
* 勉強になる

```
import XMonad
import XMonad.Hooks.ManageDocks

main=do
  xmonad $ defaultConfig
    { ...
    , layoutHook=avoidStruts $ layoutHook defaultConfig
    , manageHook=manageHook defaultConfig <+> manageDocks
    , ...
    }
```



# Haskell
* 今はやりの関数型言語
* モナドなど、本格的に理解しようとすると結構勉強になる
* C言語などとはまったく別の考え方が必要

![](images/haskell.png)



# vim
* エディタ  
* 世界で一番使いやすいエディタ(emacsよりも)  

![](images/vim.png)



# git
* バージョン管理  
* レポートや、学校の課題も管理できる  
![](images/git_commits.png)

---

# おわり
* Windows消すときは自己責任で



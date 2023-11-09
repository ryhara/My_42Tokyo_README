# My_42Tokyo_README
- 2023/03 Piscine(Entrance exam)
- 2023/05\~ Enrollment
- 42Tokyoで実装した課題の概要、使用技術の説明
## 42Tokyo 
 [ 42Tokyo Official Website ](https://42tokyo.jp/) 
 
 42Tokyoは学費完全無料、パリ発のエンジニア養成機関です。

## Level 0
### [Libft](https://github.com/ryhara/Libft)
- libc「標準Cライブラリ」に含まれる関数などの再実装　（C言語）
  - malloc, free, singly linked list

## Level 1
### [ft_printf](https://github.com/ryhara/ft_printf)
- printf関数の再実装(一部指定子)（C言語）
  - 可変長引数

### [get_next_line](https://github.com/ryhara/get_next_line)
- fgetsのような改行まで読み込んで返す関数の実装（C言語）
  - malloc, free, open, read, write

### [Born2beroot](https://github.com/ryhara/Born2beroot) (Private)
- 仮想マシンの作成、Linuxのインストール(リポジトリ空)
  - sudo, apt, user, group, ufw, ssh, LVM, cron, Debian

## Level 2
### [minitalk](https://github.com/ryhara/minitalk)
- UNIXシグナルを使用したクライアント/サーバー間の通信（C言語）
  - signal, sigaction. sigemptyset, sigaddset, usleep, pause
 
### [fract-ol](https://github.com/ryhara/fract-ol)
- MiniLibXを用いたフラクタルの描画, マンデルブロ集合, ジュリア集合（C言語）
  - [MiniLibX](https://harm-smits.github.io/42docs/libs/minilibx/getting_started.html) 

### [push_swap](https://github.com/ryhara/push_swap)
- 2つのスタックを用いたソートの最適化（C言語）
  - ソートアルゴリズム, 双方向循環リスト

## Level 3
### [minishell](https://github.com/ryhara/minishell)
- bashの再実装（C言語）
  - | , <, > , << , >> の再現
  -  echo -n, cd , pwd, export, unset, env, exitの再実装
  -  ctrl-C, ctrl-D, ctrl-\の再現
  -  environment variables, \$?, \$VARIABLE, "", ''の再現、展開
  -  その他のコマンドはexecveでPATHから実行
  -  \\, ||, &&, ;, (), は未対応
- ペア課題 ([ペアのリポジトリ](https://github.com/Mori062/minishell))

### [Philosophers](https://github.com/ryhara/Philosophers)
- 食事する哲学者の問題 ([Wikipedia](https://ja.wikipedia.org/wiki/%E9%A3%9F%E4%BA%8B%E3%81%99%E3%82%8B%E5%93%B2%E5%AD%A6%E8%80%85%E3%81%AE%E5%95%8F%E9%A1%8C))
  - 排他制御、デッドロック（C言語）

### [Philosophers-tester](https://github.com/ryhara/Philosophers-tester) (Option)
- Philosophersという課題のtestを自動で行うshell scriptを作成

## Level 4
### [miniRT](https://github.com/ryhara/miniRT)
- MiniLibXを用いたレイトレーシングプログラムの実装
  - [MiniLibX](https://harm-smits.github.io/42docs/libs/minilibx/getting_started.html)
  - カメラ、環境光、点光源、平面、球、円柱
  - カメラ位置の移動、複数オブジェクトの表示
  - Phongの反射モデル（環境光(定数)、直接光の拡散反射光、直接光の鏡面反射光）
- ペア課題 ([ペアのリポジトリ](https://github.com/YungTatyu/miniRT))  

### [NetPractice](https://github.com/ryhara/NetPractice) (Private)
- IPアドレス、サブネットマスク、ルーティングに関する練習問題

### [CPP Modules](https://github.com/ryhara/My_42Tokyo_README) (Private)
C++の練習課題
- [CPP-Module-00](https://github.com/ryhara/CPP-Module-00)
  - iostream, string, ...
- [CPP-Module-01](https://github.com/ryhara/CPP-Module-01)
  - constructor, destructor, reference, replace, switch, ...
- [CPP-Module-02](https://github.com/ryhara/CPP-Module-02)
  - fixed point number, ...
- [CPP-Module-03](https://github.com/ryhara/CPP-Module-03)
  - class inheritance, multiple inheritance, ...
- [CPP-Module-04](https://github.com/ryhara/CPP-Module-04)
  - virtual function, virtual destructor, abstract class

## Level 5
### [CPP Modules](https://github.com/ryhara/My_42Tokyo_README)
C++の練習課題2
- [CPP-Module-05](https://github.com/ryhara/CPP-Module-05)
  - try, catch
- [CPP-Module-06](https://github.com/ryhara/CPP-Module-06)
  - cast
- [CPP-Module-07](https://github.com/ryhara/CPP-Module-07)
  - c++
- [CPP-Module-08](https://github.com/ryhara/CPP-Module-08)
  - c++
- [CPP-Module-09](https://github.com/ryhara/CPP-Module-09)
  - c++

### [webserv](https://github.com/ryhara/webserv)

### [Inception](https://github.com/ryhara/Inception)

## Level 6
## Level 7

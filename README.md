# My_42Tokyo_README
- 2023/03 Piscine(Entrance exam)
- 2023/05\~ Enrollment
## 42Tokyo 
 [ 42Tokyo Official Website ](https://42tokyo.jp/) 
 
 42Tokyoは学費完全無料、パリ発のエンジニア養成機関です。

## README
42Tokyoで実装した課題の概要、使用技術の説明

### [Libft](https://github.com/ryhara/Libft)
- libc「標準Cライブラリ」に含まれる関数などの再実装　（C言語）
  - malloc, free, singly linked list

### [ft_printf](https://github.com/ryhara/ft_printf)
- printf関数の再実装(一部指定子)（C言語）
  - 可変長引数

### [get_next_line](https://github.com/ryhara/get_next_line)
- fgetsのような改行まで読み込んで返す関数の実装（C言語）
  - malloc, free, open, read, write

### [Born2beroot](https://github.com/ryhara/Born2beroot)
- 仮想マシンの作成、Linuxのインストール(リポジトリ空)
  - sudo, apt, user, group, ufw, ssh, LVM, cron, Debian

### [minitalk](https://github.com/ryhara/minitalk)
- UNIXシグナルを使用したクライアント/サーバー間の通信（C言語）
  - signal, sigaction. sigemptyset, sigaddset, usleep, pause
 
### [fract-ol](https://github.com/ryhara/fract-ol)
- MiniLibXを用いたフラクタルの描画, マンデルブロ集合, ジュリア集合（C言語）
  - [MiniLibX](https://harm-smits.github.io/42docs/libs/minilibx/getting_started.html) 

### [push_swap](https://github.com/ryhara/push_swap)
- 2つのスタックを用いたソートの最適化（C言語）
  - ソートアルゴリズム, 双方向循環リスト

### [minishell](https://github.com/ryhara)
- bashの再実装（C言語）
  - | , <, > , << , >> 
  -  echo -n, cd , pwd, export, unset, env, exit
  -  ctrl-C, ctrl-D, ctrl-\
  -  environment variables, \$?, \$VARIABLE, "", ''
- ペア課題 [相方](https://github.com/Mori062/minishell)

### [Philosophers](https://github.com/ryhara/Philosophers)
- 食事する哲学者の問題 ([Wikipedia](https://ja.wikipedia.org/wiki/%E9%A3%9F%E4%BA%8B%E3%81%99%E3%82%8B%E5%93%B2%E5%AD%A6%E8%80%85%E3%81%AE%E5%95%8F%E9%A1%8C))
  - 排他制御、デッドロック（C言語）

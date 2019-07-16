# Docker-LAMP
xamppと同様の環境をDockerで準備する
<br><br><br>


▽動作確認済み
* macOS Mojave （バージョン 10.14.4）、メモリ： 8GB、Docker： v18.09.2、docker-compose： v1.23.2
* Windows 10 Pro 64bit、メモリ： 32GB、Docker： v18.06.1-ce、docker-compose： v1.23.2
<br><br><br>



## 構成

Docker-LAMP  
├ docker-compose.yml  
├ docker  
│　 ├ db  
│ 　│ 　└ sql  
│ 　│ 　 　└ `create-sample-table.sql`  
│　 ├ nginx  
│ 　│ 　└ `default.conf`  
│　 └ php  
│ 　　　 ├ `php.ini`  
│ 　　 　└ `Dockerfile`  
└ server  
 　 ├ `index.html`  
 　 └ `index.php`  
<br><br><br>



## 解説サイト

...準備中...
<br><br><br>



## 動作イメージ

text
<br><br><br>


## 事前準備 （Provision）

* docker と docker-compose が利用できるようになっていること
<br><br><br>


## インストール （Installation）

1. このページの `Clone or download` ボタンよりリポジトリのクローンもしくはZIPダウンロード
2. ZIPダウンロードの場合は解凍
3. 解凍して出来たフォルダをDockerコマンドが有効な場所に置く
4. コマンドプロンプト（win）/ ターミナル（mac）を起動し、「3」のフォルダ内へ移動
5. `docker-compose up -d` コマンドを実行（しばらくインストールが走る）
6. ブラウザからwebサーバーアクセスを確認 → http://localhost/
7. ブラウザからwebサーバーアクセス＆php実行を確認 → http://localhost/index.php
8. ブラウザからphpMyadminとサンプルDBテーブルを確認 → http://localhost:8080/
<br><br><br>



## 使用法 （Usage）

text
<br><br><br>




## 仕様 (Specification)

* `xxx` text
<br><br><br>




## コマンド
* $ docker version / docker -v  
* $ docker-compose version / docker-compose -v  
* $ docker-compose up -d  
* $ docker-compose ps  
* $ docker ps  
* $ docker images  
* $ docker rmi xxxxx  
* $ docker stop  
* $ docker down  
<br><br><br>










## 参考
◆docker-compose による nginx + HTTP/2 + PHP-FPM7 + MySQL 環境の構築方法 &#8211; PSYENCE:MEDIA  
https://tech.recruit-mp.co.jp/infrastructure/post-12795/  

◆docker-composeをやってみたメモ - のぐそんブログ  
https://nogson2.hatenablog.com/entry/2018/11/02/235337  

◆Dockerを使ってLaravel開発環境構築 - Qiita  
https://qiita.com/A-Kira/items/1c55ef689c0f91420e81  

http://localhost/  
http://localhost:8080/  
http://localhost/index.php  

















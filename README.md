# mypkg
課題2　ROSを使用し、プログラムを作成
# リポジトリの概要
講義内で使用したプログラムをそのまま使用した  
count_up　数字が１ずつ加算され表示される  
twice　　countの数字が2倍され表示される
# 動作環境
・ubuntu20.04  
・ROS
# 使用したもの
・Raspberry Pi 3+
# 動画
https://youtu.be/_2mut1DUNh4  
# インストール及実行方法
~~~
$roscore  
$cd catkin_ws/src  
$git clone https://github.com/TNKseiya/mypkg.git  
$cd mypkg  
$cd scripts  
$chmod +x count.py  
$chmod +x twice.py
~~~
実行方法  
~~~
$rosrun mypkg count.py  
$rosrun mypkg twice.py  
~~~  
別のタブでROSを立ち上げ、下のプログラムを打ち込む  
~~~
$rostopic echo /count_up  
$rostopic echo /twice  
~~~
終了方法  
cntl + cで止まる  
# ライセンス
GNU General Public License v3.0

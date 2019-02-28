# data_challenge_kobe_2019
##仕様書

##画像を作成するためのデータセット
chuou.pickle
tomei.pickle
shibuya.pickle
shinjuku.pickle

##pythonファイル一覧
main.py
glcm.py
function.py
read_data.py

##main.py
実行するメインファイル
設定する変数は以下の通り
target：対象路線を指定
gakushu：対応する学習路線
day：予測対象日
split_num：分散個数
num_cand：類似している候補日・時間帯として抽出する個数

##glcm.py
glcmのクラス：タイムスペース図をマトリクスに変換する

##function.py
glcm内で使用する関数

##read_data
csvを読み込むためのクラス：glcmクラスとともに使用

##実行
main.pyを実行することで，ある特定の日における
首都高速道路の新宿から，ネクスコ中日本の中央道，
首都国則道路の渋谷から，ネクスコ東名道の道路の将来の状態をあてる．

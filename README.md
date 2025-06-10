これ見たら分かりやすいです
https://youtu.be/SWcuiUHfj5M
# 使い方 #
1.https://matheowis.github.io/HDRI-to-CubeMap/ にアクセスし、HDRIをアップロードというところからskyにしたい画像をうｐする  
2.保存をクリック  
3.一番下を選択  
<img src="https://github.com/user-attachments/assets/94728cca-bc83-4a6d-8702-b316d0056444" width="128px">  
4.解像度を2048くらいに高くする(これをしないとskyが荒くなります)  
<img src="https://github.com/user-attachments/assets/fdaa062e-8369-4857-8e36-393c8812f7ef" width="320px">  
5.プロセスをクリック  
6.保存をクリック  
7.このリソースパックの`textures\environment\overworld_cubemap`を開く  
8.そしてさっき作ったキューブマップの画像6つをこの中にコピーする  
9.画像の名前をそれぞれ↓のように変更する  
```
pz = cubemap_0
px = cubemap_1
nz = cubemap_2
nx = cubemap_3
py = cubemap_4
ny = cubemap_5`
```
10.出来たらこのリソースパックフォルダ内の2つのファイルと1つのフォルダーを全部選択して、zip形式で圧縮する  
11.拡張子を.mcpackに変更する
12.ダブルクリックでマイクラにインポート、有効化したら完了

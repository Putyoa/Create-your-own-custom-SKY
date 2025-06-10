これ見たら分かりやすいです
https://youtu.be/SWcuiUHfj5M
# 使い方 #
_**1**_.https://matheowis.github.io/HDRI-to-CubeMap/ にアクセスし、HDRIをアップロードというところからskyにしたい画像をうｐする  
_**2**_.保存をクリック  
_**3**_.一番下を選択  
<img src="https://github.com/user-attachments/assets/94728cca-bc83-4a6d-8702-b316d0056444" width="128px">  
_**4**_.解像度を2048くらいに高くする(これをしないとskyが荒くなります)  
<img src="https://github.com/user-attachments/assets/fdaa062e-8369-4857-8e36-393c8812f7ef" width="320px">  
_**5**_.プロセスをクリック  
_**6**_.保存をクリック  
_**7**_.このリソースパックの`textures\environment\overworld_cubemap`を開く  
_**8**_.そしてさっき作ったキューブマップの画像6つをこの中にコピーする  
_**9**_.画像の名前をそれぞれ↓のように変更する  
```
pz = cubemap_0
px = cubemap_1
nz = cubemap_2
nx = cubemap_3
py = cubemap_4
ny = cubemap_5`
```
_**10**_.出来たらこのリソースパックフォルダ内の2つのファイルと1つのフォルダーを全部選択して、zip形式で圧縮する  
_**11**_.拡張子を.mcpackに変更する
_**12**_.ダブルクリックでマイクラにインポート、有効化したら完了

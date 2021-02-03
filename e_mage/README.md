# e_mage
## e_mage.image
画像に関するあれこれ

|method|description|
|---|---|
|convert_3ch|(H, W) or (H, W, 1)の画像を(H, W, 3)にする|
|weighted_sum|重み付きで画像を足し合わせる|
|get_img_table|画像をテーブル状に並べる|
|get_video|画像群をmp4で保存|
|get_gif|画像群をgifで保存|
|put_text|画像上に文字を書く|

## e_mage.hetmap
ヒートマップに関するあれこれ

|method|description|
|---|---|
|generate_gaussmap|2Dガウスフィルタを出力|
|generate_heatmap_sequence|ヒートマップを出力or保存|
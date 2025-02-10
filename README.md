# Holowatch
3D像を空中に表示するApple Watch 拡張ツール  
Apple Watch extension tool to display 3D images in mid-air

<img width="173" alt="holowatch" src="https://github.com/user-attachments/assets/52b2e76e-26d8-48bf-bbcf-25c5c67872a6"/>

<img width="173" alt="holowatch-gif" src="https://github.com/user-attachments/assets/ded59768-1e19-4e05-bebe-f703ca3249a9"/>

## Preparations
- 3Dプリンター / Preferred 3D Printer (FDM/Resin)
  - ELEGOO Mars 2 Pro
- Apple Watch 
  - SE 40mm
- アクリル板 / 1 Acrylic Board (2mm)
  - 2mm厚のアクリル板を使用
  - ダイソーで購入 https://jpbulk.daisonet.com/products/4984355189930
  - 厚すぎると綺麗に反射しない
- 反射板 / 2 Reflectors
  - ダイソーで購入 https://jpbulk.daisonet.com/products/4549131255317
  - プリズム製より樹脂製の方が解像度高

## How to Make
<img width="173" alt="スクリーンショット 2025-01-19 15 56 18" src="https://github.com/user-attachments/assets/c9ef80e1-0911-4f48-956f-9a92aa1c3078" />

[日本語]

1. "holowatch.stl" をダウンロードしスライサーソフトで開く (サンプルはCHITUBOXを利用)
2. 任意の形式にスライスし印刷する (Mars 2 Pro は .ctb 形式にスライス)   
  a. 必要に応じてサポートをつけてください
  b. 光造形の場合、斜め方向に出力する or 分割出力するなど工夫してください。垂直方向に出すと自重で歪みやすいためです
3. アクリル板を任意の長さに切り出し、反射板を取り付ける
4. Apple Watch を装着し、動画像を再生する  
[memo] Apple Watch のバンドが通しづらい場合はヤスリで削って微調整してください  

[English]
1. Download "holowatch.stl" and open it in slicer software (CHITUBOX is used as a sample).  
2. Slice and print it in the desired format (Mars 2 Pro slices to .ctb format).  
    a. Add supports as necessary.  or resin printing, consider outputting at an angle or in sections.   
    b. Vertical output can lead to deformation due to weight.   
3. Cut the acrylic board to the desired length and attach the reflector.  
4. Wear the Apple Watch and play the video.  
[memo] If the Apple Watch band is difficult to pass through, adjust it with a file.  

## Open to Improvements
ぜひお手持ちの Watch に応じてデータを改変してみてください。  
使用、複製、改変、再配布についてはMITライセンスに則るようお願いします。   
  Please modify the data according to your own Watch.   
  Please follow the MIT license for usage, reproduction, modification, and redistribution.  

## Reference
- [タッチレス空中インタフェースとしての3Dディスプレイの利用](https://www.ipsj.or.jp/dp/contents/publication/55/S1403-S07.html) - 会誌「情報処理」Vol.64 No.8（Aug. 2023）「デジタルプラクティスコーナー」
  - ホログラムの基本原理を参考に作成しました
- [ホロスター フレームセット4244 - ホログラム株式会社](https://ho-lo.jp/products/hardware/holostar-fsm44/)
  - Apple Watch の取り付け部分の設計を参考にしました

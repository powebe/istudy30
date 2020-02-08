# SliderMulti-v0xx 使用說明：
- 利用 broadcast "SliderOn" 事件啟動，用滑桿左右移動
- 選擇輸入數字之結果，存放在 gSliderValue 
- 用 gActiveSpriteName=自訂的lcSpriteName 搭配 broadcase 來區分呼叫物件
## 設定：
- gActiveSpriteName, gSliderValue 必需是 global
## 參數：
- lcMaxValue 設定輸入最大值
- lcPosX, lPosY, 設定第出現的位置中點
- lcSize 設定大小 
- lcBetweenX (間距自動計算)
- lcColor 設定顏色 
##  特效：
無
## 註：
在 gActiveSpriteName=lcSpriteName 來避免 obj 重覆使用，會出現衝突的問題
# ==changelog==
- v014: 2020/02/08
修正按下滑鼠後，有時橫桿不會消失的 bug
- v013: 2020/02/02
可以產生2個以上的滑桿 (未完成)
- lcMaxSliders = 2，但回傳值未完成
- v010: 2020/01/31初版
SliderMono-v010

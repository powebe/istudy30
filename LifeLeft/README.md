# LeftLeft 使用說明：
- 利用 broadcast "showLife" 事件啟動
- 改變 gLifeLeft 來決定剩幾條命
- 用 gObjName 搭配 broadcase 來區分呼叫物件
## 設定：
- gLifeLeft、gClearLifeClone 必需是 global
## 參數：
- lcX, lcY, 設定第1個出現的位置
-  lcSize 設定大小 
-  lcBetweenX (間距自動計算)
##  特效：
放在自訂 block 中
## 註：
在 forever block 中，應使用用 gObjNsame=lcObjNsame 來判斷避免 obj 重覆 時，會出現誤刪 clone 的問題
# ==changelog==
- v013: 2019/11/04 fix 用 gObjName 搭配 broadcase 來區分呼叫物件
- v01x: 「增加命」，如何處理?
- v010: 2019/10/31初版

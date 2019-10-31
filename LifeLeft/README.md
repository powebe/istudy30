# LeftLeft 使用說明：
利用 broadcast "showLife"
## 設定：gLifeLeft、gClearLifeClone 必需是 global
改變 gLifeLeft 來決定剩幾條命

## 參數：
- lcX, lcY, 設定第1個出現的位置
-  lcSize 設定大小 
-  lcBetweenX (間距自動計算)
##  特效：放在自訂 block 中
- 註：forever 中，用 lcObjNsame 來避免 obj 重覆 時，會出現誤刪 clone 的問題
# ==changelog==
- v01x: 「增加命」，如何處理?
- v010: 2019/10/31初版

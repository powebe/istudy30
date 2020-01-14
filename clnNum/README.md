##使用說明：
  一開始利用 broadcast "createCloneNum" 啟動/結東
  或利用 createScore() 創建新的數字群組

  參數：lcPosX, lcPosY, 設定出現位置
              lcSize 設定數字的大小
              lcBetweenX 設定數字的間隔
              lcGroup 設定數字的群組編號，預設 = 99
              lcScore 設定數字的內容，預設 = 10位數
  使用方法：
              1. 更新 Score 的內容
              2. 將 Score 換成別的變數，例如 timeer
  結果： 更新 global Score 變數，即可自動變更顯示的數字
  註：gClearClone、gJ，都要設成 global (for all sprite)
## ==changelog==
v022: 2020/1/14版 clnNum-靠左-v22
          改成用 變更 clone 內容，不是重新建 clone
v021: 2020/1/12版 clnNum-靠左-v22
          改成靠左
v020: 2019/6/6 版
         clnNum-v20.sb2

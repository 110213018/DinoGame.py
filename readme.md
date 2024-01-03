# 尋找顏⾊的⼩恐⿓
## 動機：
⼩恐⿓因為linux考不及格，被⽣氣的助教們變成灰⾊的了！！⼩恐⿓聽說只要穿越了
⼤森林，抵達魔法洞⽳，就可以找回顏⾊，快來幫助⼩恐⿓找回顏⾊吧！
## 功能：
會有⼀台內裝有紅外線感測的復古式遊戲台跟⼀個不透光的⿊⾊紙盒(把其中⼀⾯打
洞打成恐⿓的樣⼦，在洞上⾯再貼上很透光ㄉ⿊布，透光部分為恐⿓造型)，箱⼦裡
⾯會放⼀個rgb led燈。遊戲為類似google chrome的⼩恐⿓遊戲。投幣之後，遊戲台
會⽤紅外線感測是否有投幣，如果有投幣，就可以開始⽤按鍵玩dinoGame。開始遊
玩後，如果每成功跳過10個障礙，燈就會亮⼀種顏⾊，成功跳過30個障礙之後，燈
就會閃爍變⾊，遊戲畫⾯也會跳出通關的通知：反之，如果撞到障礙物，就會失去顏
⾊且遊戲結束。⼀旦遊戲結束，就要重新投幣才能繼續遊玩。
## 硬體設備：
- Raspberry pi 3
- 麵包板專⽤線
- 麵包板
- 巨型ENTER鍵
- 杜邦線
- IR感測器(180度)
- led燈
- register
- 紙箱
- moli捐贈的電腦螢幕
## 軟體
- python
- pygame
## 前置下載
1. pygame
2. python
## 執行過程
- 程式碼
  - dinoGame.py：恐龍遊戲
- 硬體準備
  - raspberry pi環境組裝
  - 遊戲機台組裝
  - 紅外線感應裝置
  - LED燈裝置
## DinoGame START！
## 心得回饋&遇到的困難
1. raspberry pi環境組裝
因為在製作過程中，raspberry pi疑似因為過熱燒壞了，所以再重新設定raspberry pi上花了很多的心力跟時間。
2. 遊戲機台組裝

3. 紅外線感應裝置

4. LED燈裝置
   
5. dinoGame遊戲
原本是用ursino開發遊戲，但是當要在樹莓派上運行時，跳出提示說要安裝Panda3d，但在安裝上有困難，所以最後決定用pygame的形式表現出小恐龍遊戲。再加上，原本要外接的迷你螢幕，因為性能不足，無法顯示遊戲，所以最後決定用HDMI線的方式連接到性能較完善的電腦螢幕，最後就成功了~！！

6. 程式碼整合

## 工作分配
## 參考資料
遊戲軟體參考：https://github.com/maxontech/chrome-dinosaur
紅外線感測參考：
led裝置參考：https://www.youtube.com/watch?v=kfb34fn9zpo&t=276s
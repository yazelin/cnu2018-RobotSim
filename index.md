# 卓智創互動科技
* 官網：[http://www.wtech.com.tw/](http://www.wtech.com.tw/)
* Facebook：[https://www.facebook.com/wisetech.dakuo/](https://www.facebook.com/wisetech.dakuo/) 



## 業界在互動應用中使用哪些工具?
1. Unity [wiki](https://zh.wikipedia.org/wiki/Unity_(%E6%B8%B8%E6%88%8F%E5%BC%95%E6%93%8E))
1. Maya [wiki](https://zh.wikipedia.org/wiki/Maya)
1. 3dMax [wiki](https://zh.wikipedia.org/wiki/3ds_Max)



## Unity應用案例(廣告時間)
* 例：[愛之味體感互動遊戲](https://www.facebook.com/wisetech.dakuo/videos/885588164860007/)
* 例：[互動射擊裝置](https://www.facebook.com/wisetech.dakuo/videos/664104040341755/)



## Unity 還有...?
Unit還有這種使用方式(之一)?! 只有想不到，沒有做不到。
> 想像力是你的超能力



## Unity+leapmotion 操控 工業用機器手臂
* [連結1](https://www.facebook.com/wisetech.dakuo/videos/1212236958861791/)
* [連結2](https://www.facebook.com/wisetech.dakuo/videos/1225804447505042/)



## Unity只能使用在互動應用中?
* 這些工具能只能做遊戲、APP或AR/VR嗎?
* 擔心學了以後無處可用嗎?
* 這幾週的課程內容會教大家，我們是怎麼把工具當作工具用(廢話?)



## 解決問題的流程
1. 發現問題
1. 假設解決辦法
1. 使用工具製作出解決辦法
1. 使用解決辦法來解決問題



## 例：RobotSim Webplayer

- 發現問題
  - 機器手臂一台幾十到幾百萬，客戶在購買之前對它不了解就降低了購買意願，如果可以先玩玩看再決定買不買呢?

- 假設解決辦法 
  - 不如我們提供手臂讓客戶玩玩看?(公司不會買手臂來只為了讓客戶玩，玩完後決定不買不就浪費錢了)
  - 那模擬一個虛擬的機器手臂讓客戶玩看看?(可能可行，那要來公司玩嗎?還是可以線上玩?)
> 如果製作一個線上可以模擬機器手臂運作的機器手臂模擬器應該可行?(假設解決辦法)

- 使用工具製作出解決辦法
  - 製作網頁中的手臂模擬器 -> Unity 可以製作完成後輸出成WebGL 在現代的瀏覽器中可以模擬3D畫面 讓客戶模擬手臂運作
  - 機器手臂模型 -> 由機器手臂公司可下載得到 轉檔成可輸入Unity的格式即可

- 使用解決辦法來解決問題
  - 我們把模擬器放到網站上了
  - 網址在這邊 [RobotSim WebPlayer](http://www.wtech.com.tw/robotsim)
  - 歡迎大家來玩~~~ 


## 同學們的遊戲時間
大家邊玩邊我們邊了解一些機器手臂的運作及相關背景知識 
- 在模擬器中我們可以學到這些
- ![Image](./img/RobotCoordinateSystem.jpg)
  - 座標系
    - WORLD
    - BASE
    - TOOL
    
  - 操作方式
    - XYZ ABC
    - AXIS
    
  - 運動指令
    - PTP
    - LIN
    - CIRC(網頁版的模擬器中沒有) 
    
  - 軸極限  
  - ![Image](./img/RobotAxis.jpg)
    - A1~A6
    
  - 手臂程式執行方式 
    - 先教點 
    - 用指令讓手臂重現動作 
    
    
- 實際上機器手臂的硬體有這幾個部份 
1. 機器手臂 
1. 機器手臂控制器 
1. 機器手臂教導盒 
1. 連接線
  
 ![Image](./img/RobotSystem.jpg)



## 帶著好奇心探索新世界-RobotSim
 想看看在Unity內可以怎麼玩機器手臂嗎?
Unit還有這種使用方式(之二)?! 只有想不到，沒有做不到。
> 想像力是你的超能力 

- RobotSim 下載-安裝-試用
  - 影片參考 [連結](https://www.youtube.com/watch?v=xv4v_fOwAC0&index=20&list=PLYLTPJkULAAZZuNW2s2tX-KWQOus7sAAo).
- RobotSim-教點-程式-模擬
  - 影片參考 [連結](https://www.youtube.com/watch?v=4Gk7K88B10c&index=21&list=PLYLTPJkULAAZZuNW2s2tX-KWQOus7sAAo).
- RobotSim-設定Tool-更新點位-模擬動作
  - 影片參考 [連結](https://www.youtube.com/watch?v=NLA6A_qWDgs&index=22&list=PLYLTPJkULAAZZuNW2s2tX-KWQOus7sAAo).
- RobotSim-設定Base-設定手臂-匯出程式
  - 影片參考 [連結](https://www.youtube.com/watch?v=izkk5MW-FeY&index=23&list=PLYLTPJkULAAZZuNW2s2tX-KWQOus7sAAo).

## 在RobotSim 中我們還能做什麼?
- 加入夾爪讓手臂可以取放物件? OK
- 把手臂放在滑軌上讓手臂運作空間更大? 好
- 規劃一條生產線? 可以
- 加入其他品牌的手臂? 當然
- 設計一套自動化流程，產生各種手臂的運動程式? 沒問題

## 你想做什麼?
[歡迎加入RobotSim討論區](http://forum.wtech.com.tw/viewforum.php?f=17&sid=4a42cdd8643e5518dd23f732ca23f0c4).


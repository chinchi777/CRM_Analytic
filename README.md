# CRM_Analytic
# CRM客戶分析


 #### 摘要：
 從kaggle下載電商訂單資料利用RFM模型分析客戶購軌跡製作客戶貼標， 並利用模型預測出客戶未來的購買頻率及金額，最後得出客戶價值。

#### 方法：

第一部分RFM分析：利用RFM模型做出客戶的10類貼標，並用treemap視覺化進一步分析各類客戶數據。

第二部分客戶價值分析：利用lifetimes套件做預測將數據分割套入BGF模型預測出下一次的購買金額及頻率。再利用GGF模型預測未來購買金額及客戶價值CLV。

#### 結果：

分析出兩組關鍵分群，需針對族群名單做銷售投放： 

​高度參與群體champions冠軍客戶及loyal customers忠實客戶此群體包括了最頻繁消費的顧客及最高的平均交易額，分別佔總客戶比15%及17%，平均交易金額為6852 及2746美金，需要持續維持客戶的高度參與並促進更多購買。
需要激勵群體 can't loose不容失去客戶及at risk有風險客戶此兩群體客戶分別佔總客戶比1.7%及14%，都是近一段時間無消費但是過去消費軌跡良好交易金額高需要再次將客戶喚醒，制定可激勵購買的廣告策略。  

預測未來交易：

套入模型結果預測未來一個月平均客戶交易次數為0.5次最高為9次，平均交易額為421美金，客戶價值平均為240美金，由此參考值可規劃出下一個月的行銷預算。

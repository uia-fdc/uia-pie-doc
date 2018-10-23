ProcessING Inspection Eyes
===

P.I.E. 主功能為生產資料的收集、分析、檢測計畫的制定與處置策略。不同于 SPC 在制程完成後才對收集到的資料進行統計分析，P.I.E. 可在制程進行中同步追蹤，並在檢測到問題後立即發出警告或報警。

P.I.E. 在不影響效能的前提下，提供高擴充性與高資料量儲存，並可配合營運環境進行分區配置。P.I.E. 支援作業與資料備援，可確保在部分主機故障時系統能持續運作。

## Features

### Run Data with Replica
* 完整紀錄製造過程中產生的資料，並自動備份以實現容錯。

* 當節點發生故障時，可自動被正常節點取代，無須重啟系統。

### Scalable and Performant
* 高擴充性，支援 300 以上的資料收集點同步進行資料收集。

* 資料根據需求進行優化儲存，確保在大量資料下保持穩定的查詢效率。

### Decentralized
* 無單一弱點。

* 各工作節點可獨立運作並互相備援，確保系統的可靠度。


## System Overview

![](images/dcp1.png?raw=true)
## Solutions
#### Data Collection
* 收集廠內各式設備或感測器的資料如壓力、溫度等。

* 根據製造履歷將資料進行分群與歸檔。

* 線上保留一年完整資料，透過分區儲存達到查詢優化。

![](images/dc_4.png?raw=true)
![](images/dc_6.png?raw=true)
![](images/dc_8.png?raw=true)

### Inspection Plan
* 對進行中的製程進行即時檢測。

* 利用 Java Script 客制化演算法進行資料追蹤與分析。
    * RAW
    * MEAN
    * MAX
    * MIN
    * RANGE
    * COUNT
    * SUM
    * SLOPE
    * DYNAMIC_SLOPE
    * FIRST_POINT
    * LAST_POINT

![](images/ia_2.png?raw=true)
![](images/ia_4.png?raw=true)
![](images/ia_5.png?raw=true)
![](images/ia_7.png?raw=true)

### OOC Integration
* 與 MES 整合進行錯誤通報與處置。

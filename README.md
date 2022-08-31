# NCHU_WCCC_weekly_progress
### 以下是碩士在學期間的周進度：
### 常規的進度是一周要讀一篇論文做呈報告，其中有幾周是在做其餘研究。<br>
### （像是研究藍芽規格、嵌入式框架研究、基礎知識學習、投稿論文撰寫與畢業論文撰寫）
### 檔案連結：
### https://drive.google.com/drive/folders/15CMXmRRn5JqpiFRa_zTFFmjwhGvCzgqK?usp=sharing

| 時間 | 周進度內容 |
|  ----  | ----  |
|  2022/7/23  | 這週的周進度是將論文改成投比賽的論文，目前是先把格式轉換成比賽要的格式。  |
|  2022/7/16  | 這週的周進度是將我程式跟環境都打包成虛擬機，並且交接給學弟們  |
|  2022/7/9  | 這週的周進度是將我的實驗環境移到虛擬機上，目前完成了虛擬機跟zephyr 環境架設。接下來要打包程式移到虛擬機上|
|  2022/7/2  | 準備論文程式交接  |
|  2022/6/17  | 完成本周提及的 trade off 實驗也加進論文中，  |
|  2022/6/11  | 撰寫第五章內容，修改第三，四章內容與完成新實驗  |
|  2022/5/28  | 本週進度為量測提出的對稱式加密與原本的AES效能差距，接下來會做非對稱式效能量測與增加變因測認證效能。  |
|  2022/5/21  | 這週的周進度是<br>撰寫應用層的比較對象，目前已經完成接下來會進行效能測試。  |
|  2022/5/14  | 這週的周進度是<br>撰寫應用層的比較對象，藍牙通訊GATT的問題解決了。<br>正在做交換封包內容的正確性，花比較多時間是因為 Zephyr 網路上資源比較少而且有些是錯的。導致花比較多時間在 Debug  |
| 2022/5/7  | 這週的周進度是<br>撰寫應用層的比較對象，已經完成安全機制的演算法與函式庫改寫。<br>剩下部分是藍牙通訊，卡在比較對象封包在GATT層的設計比較困難。<br>完成後就可以進行測試了 |
| 2022/4/30  | 論文第三章撰寫，目前還在撰寫與修改中。會在五月一號結束前交給老師。 |
| 2022/4/16  | 這周的周進度是<br>完成論文第二張撰寫，以及實做APP層比較對象。<br>APP層比較對象有同時使用多種ECC加密，原本library不支援同時使用，所以正在改寫library讓它可以同時使用多種ECC金鑰。 |
| 2022/4/2  | 這周的進度是完成提出方法和規格方法在認證階段的效能比較，並實際作圖。<br>比較分為時間和能耗，設定是以五種不同傳輸功率以一公尺的距離進行量測（每個實驗點做20次實驗）。不以距離為變量的原因有在報告中提及，之後的進度報告會詳細說明。<br>以結果來說，相較於規格提出的方法認證時間減少23.2% 消耗電量減少13.37%。 |
| 2022/3/26  | 整理論文的相關文件與撰寫第一章，目前完成到動機的一半。接下來會繼續完成剩下的部分 |
| 2022/3/19  | 這周的周進度是<br>整理離島論文的相關文件，與寫離島論文的簡介、實驗參數與系統模型。目前簡介、實驗參數與系統模型初步完成（部分數據與貢獻在後面實驗撰寫完成後會回填相關數據） |
| 2022/3/12  | 這周進度是讀一篇論文<br>"Painometry: Wearable and Objective Quantification System for Acute Postoperative Pain", <br>這篇論文是一篇實作的論文，目的是用分類器來判別人類對痛苦的量化來避免止痛藥物濫用。作者收集了多種 sensor 數據(SIP,EEG,GSR,PPG)經過量化在透藍芽傳輸，接著使用 SVM 作為分類器來判別痛苦等級。 |
| 2022/3/5  | 這周進度是讀一篇論文<br>"Keys from the Sky: A First Exploration of Physical-Layer Security Using Satellite Links", <br>這篇論文提出用 GNSS 信號生成密鑰的方法，用信號生成密鑰的方法很常見。但作者的情境是與衛星設備進行信號交換，會遇到空氣介質以外的干擾(像是電離層)。作者將會遇到的干擾納入參考並正規化處理，並實際使用設備與衛星做實驗。 |
| 2022/2/19  | 這周進度是讀一篇論文<br>"A Novel Chaos-Based Physical Layer Security Transmission Scheme for Internet of Things", <br>這篇論文提出一個強化 OFDMA 編碼安全性的機制，原本的 OFDMA 的傅立葉變換矩陣原本是按照索引值順序的。會導致在傳送時的資料隨機性下降造成安全問題。作者基於 OFDMA 傅立葉變換的機制下，用三維度(X軸 Y軸 先後資料運算)的隨機序列來進行底層加密。論文整體確保了 OFDMA 資料的隨機性宇資料的安全性，但沒考量到 OFDMA 的資料傳輸和加密參數交換的問題，並且所需加密參數過大問題。 |
| 2022/2/12  | 這周的周進度是完成 ECC 加密程式的設計和 debug ，目前完成測試證明我的設計在 Zephyr 上是可行的。接下來是要寫應用層的 GATT feature 來讓上層能夠用相對應的資料結構來交換資料。 |
| 2022/1/28  | 這周進度是測試我的論文中協議設計的部分，接續週三的報告做程式的測試。目前確認AES程式可以執行，ECC部份還在測試。 |
| 2022/1/22  | 這周進度是實作我的論文中加密演算法的部分 (不包含協議設計)<br>Zephyr 的加密機制是基於 TinyCrypt 函式庫實作加密演算法，根據標準的 TinyCrypt 函式庫修改了符合論文方法的版本。<br>實際做的內容有:新增一套 AES 的加解密機制 (有使用 shiftKey 的功能) 、實作 xor 和加減法兩個版本的 ECC 資料加解密演算法 (原本 TinyCrypt 不支援 ECC 資料加解密演算法) |
| 2022/1/8  | 這周進度是讀一篇論文<br>"Efficient Post-Quantum TLS Handshakes using Identity-Based Key Exchange from Lattices", <br>這篇論文提出一個新的基於ID的交換密鑰的認證機制，方法基於 CCA-secure encryption 的機制修改。方法中多使用一種的 hash 來降低破解機率，使用 pre-quantum 和 post-quantum 來證明能耗低於於其他方法 3.7 倍。 |
| 2022/1/1  | 這周進度是讀一篇論文<br>"Block-Based Access Control for Blockchain-Based Electronic Medical Records (EMRs) Query in eHealth", <br>這篇論文提出一個使用區塊鍊交換資訊的機制，特色在於免代理這或是第三方認證的角色。方法使用橢圓曲線方式做認證後使用AES做訊息交換。區塊鍊存的是 token 讓其他人做認證使用，為了避免區塊鍊竄改作者將區塊鍊中的 token 都加入新區塊的橢圓曲線運算。 |
| 2021/12/25  | 這周進度是讀一篇論文<br>"Securing Vehicle ECU Communications and Stored Data", <br>這篇論文提出一個在車內網路密碼學和數位簽章的機制實現的安全架構，目的是為了控制車內各感測器及裝置間的通訊。方法透過建立中控設備作全部裝置個別的認證，透過共享金鑰方式建立加密連線。優點是能讓各個終端只需存較少的資訊，但中控設備需要儲存更多的資料。方法上數位簽章使用 ECC based 的方法，加密使用對稱式加密(細節並未提及)。 |
| 2021/12/11  | 這周進度是讀一篇論文<br>"New Plain-Text Authentication Secure Scheme for Implantable Medical Devices with Remote Control", <br>這篇論文提出一個新的明文認證的機制，這類型的機制主要針對認證用戶為主，加密不是這類機制的考量。作者基於標準演算法 Diffie-Hillman method 做修改完成認證機制，使用 同餘乘法 與 指數運算 的數學特性來產生雙方設備的驗證碼。 |
| 2021/12/4  | 這周進度是讀一篇論文<br>"Privacy-Preserving Graph Encryption for Approximate Constrained Shortest Distance Queries", <br>這篇論文的情境是在資料已加密的圖形中尋找最低短路徑的方法，問題的重點在圖形中的節點與 cost 是隱私資料，所以要在資料上加入雜訊。作者使用 2 hop 最短路徑 以及有 限制的閥值來減少不必要的搜尋，來達成相比其他方法更好的效能。 |
| 2021/11/27  | 這周進度是讀一篇論文<br>"Efficient Privacy-Preserving Similarity Range Query based on Pre-Computed Distances in eHealthcare", <br>這篇論文作者設計一個隱私保護計算的方法，這類型問題是做在有限的分享使用者資訊的情況下不洩漏使用者隱私資料。與原本傳統方法相比，作者透過預先計算歐式距離來減低搜尋計算時間。 |
| 2021/11/20  | 這周進度是讀一篇論文<br>"SHIPHER: A new family of light-weight block ciphers based on dynamic operators", <br>這篇論文作者設計一個新的對稱是加密方式，相較於AES有更低的記憶體使用率。透過動態的運算子和 hash 組成 round 加密來達成加密的複雜度 (AES都過篇一根矩陣運算)。 |
| 2021/11/12  | 這周進度是讀一篇論文<br>"IoTGaze: IoT Security Enforcement via Wireless Context Analysis", <br>這篇論文作者設計基於數據上下文傳輸的應用服務安全檢測框架，針對自然語言處理技術的無線數據傳輸應用。作者設計一個生成器能夠生成使用者及封包順序，透過是偵測用戶及流程檢查的機制來做到避免攻擊的安全框架。 |
| 2021/11/5  | 這周進度是讀一篇論文<br>"Trust-Based DoS Mitigation Technique for Medical Implants in Wireless Body Area Networks", <br>這篇論文作者針對 WBAN 會有一個中控節點(sink node)來收集人身上的資料，這樣的節點對於 DoS 的攻擊很敏感。作者對 sink node 分成三個環境設定不同的閥值，在實驗能顯示相比最原始的通訊相比能有效的提升 through put 及有效的將惡意封包捨棄。 |
| 2021/10/30  | 這周進度是讀一篇論文<br>"Light-Weight Solution to Defend Implantable Medical Devices against Man-In-The-Middle Attack", <br>這篇論文作者設計一個新型的簽章驗證方法，作者使用一個隨機數系統 Chaotic 及非線性轉換方法 Henon 來完成信息認證。傳統的方式是用單向雜湊，作者使用 Chaotic-Henon 來完成。方法特性是相比單向雜湊速度更快，但作者並沒有考量資料被竊聽的情境。 |
| 2021/10/23  | 這周進度是讀一篇論文<br>"A Robust and Reusable ECG-Based Authentication and Data Encryption Scheme for eHealth Systems", <br>本篇論文基於人體 ECG 資料幾乎是唯一的特性來做為 ID 做到不需要中控認證的機制，擁有 ECG ID 後使用訊息認證機制來完成密鑰交換作加密。作者使用安全性分析使用破解機率算出期望值並證明提出的密鑰是 uniformly distribution。 |
| 2021/10/16  | 這周進度是讀一篇論文<br>"LiSA: A Lightweight and Secure Authentication Mechanism for Smart Metering Infrastructure", <br>這篇論文提出在智慧電網的安全性機制。其方法基於 ECQV, ECDLP 和 ECDHP 密碼學特性的認證與交換密鑰機制，方法主要是產生 ECC 加密及基於時間與 ID 的認證機制。 |
| 2021/10/7  | 這周進度是讀一篇論文<br>"Secure outsourcing of scalar multiplication on elliptic curves", <br>這篇論文是考量當使用外部資源做計算時的資料安全問題，作者利用同一橢圓曲線作加法及乘法混合運算。<br>透過 ECC 的密鑰特性使得外部資源能協助運算，但無法還原實際運算的數值。 |
| 2021/9/25  | 這周進度是讀一篇論文<br>"A Portable Wearable Tele-ECG Monitoring System",<br>這篇論文作者實作出一個乾性電極的心電圖及心跳量測的系統，用手機收集感測數據到醫生使用網頁查看病患數據。並找30個測試者測試量測心電圖及心跳有99.23%的準確性。 |
| 2021/9/18 | 這周進度是讀一篇論文<br>"SEAT: Secure Energy-Efficient Automated Public Transport Ticketing System", <br>這篇論文提出使用BLE作為基礎通訊技術的 Public Transport Ticketing System，其提出的基於能耗及匿名等考量選擇 BLE。做這提出的方法是在應用層實作TLS來做到安全要求，並有針對干擾環境進行能耗測試。 |
| 2021/9/11  | 這周進度是讀一篇論文<br>"AdaptaBLE: Data Rate and Transmission Power Adaptation for Bluetooth Low Energy", <br>這篇論文在BLE中，透過調整 TX power 和 Data rate 來提高 Packet Reception Ratio。並將提出方法實作，比起原本固定 TX power 和 Data rate 的方法能達到更好的效果。 |
| 2021/9/4  | 這周進度是讀一篇論文<br>"Efficient Bluetooth Low Energy Operation for Low Duty Cycle Applications", <br>這篇論文提出考量 BLE 的多種應用情境跟裝置特性，BLE 中最耗電的就是廣播。作者針對這點，透過 BLE 對 Duty Cycle 的機制調配整個廣播周期來做到保持廣播品質又做到最低能耗。 |
| 2021/8/21  | 這周進度是讀一篇論文<br>"A Real Time and Non-Contact Multiparameter Wearable Device for Health Monitoringm", <br>這篇論文是一篇實作的論文，目的是讓藍芽裝置能同時接收多種不同型態資料(溫度  腦電波及跌倒偵測)。因為 sensor 特性有實作特殊電路避免 sensor 敏感。作者使用的是 BLE4.0 而不是 5.0 以上，並沒有提及GATT相關數據的設計。所以實作的主要考量點在腦電波的數據收集研究。 |
| 2021/8/14  | 這周進度是讀一篇論文<br>"A Novel Hierarchical Architecture Design for Secure Wireless Fieldbus Systems", <br>這篇論文考慮加密後傳資料 bit error 所造成的解密錯誤，基於目前流行的 AES 方法。AES 根據區塊加密，做這透過加大區塊同時傳送不同區塊大小的密文做資料的復原。本論文有降低了錯誤率但未考慮傳輸成本。 |
| 2021/7/31 | 這周進度是讀一篇論文<br>"On Misconception of Hardware and Cost in IoT Security and Privacy", <br>這篇論文提出過去在 IoT 認為資源不足的原因導致安全性難以實現，作者透過實作來證明在新式的設備下沒有此疑慮。作者在 ESP32 及 CC3220 上並透過 ATECC608A 作為加密晶片，來做測試。結果顯示硬體能對一些加密方法做硬體加速，所以對裝置負擔沒有過去想像的重。 |
| 2021/7/17  | 這周進度是讀一篇論文<br>"On the Design of Blockchain-Based Access Control Protocol for IoT-Enabled Healthcare Applications", <br>這篇論文提出使用區塊鍊的機制來記錄醫療情境中的安全參數，為了不透漏加密資訊透過 hash 對加密資訊及時間作驗證。優點是能夠透過整個區塊鍊機制避免單一節點受到攻擊 |
| 2021/7/10  | 這周進度是讀一篇論文<br>"Secure Authentication and Key Agreement Protocol for Tactile Internet-based Tele-Surgery Ecosystem", <br>這篇論文提出在遠端手術觸覺物聯網的安全性議題，使用 第三方認證 以及 ECC 加密來完成密鑰的交換機制。提出的方法有通過安全性框架 AVISPA 的測試。 |
| 2021/7/3  | 這周進度是讀一篇論文<br>"CFB-AES-TURBO: Joint Encryption and Channel Coding for Secure Satellite Data Transmission", <br>這篇論文考量到加密密文傳輸對於通道增益的引響，並控制了 block size。<br>AES 加密後密文不適合傳輸，並以 TURBO 編碼解決。TURBO 編碼需要進行 block size 控制，作者也處理這個問題 |
| 2021/6/26  | 這周進度是讀一篇論文<br>"FREE: A Fast and Robust Key Extraction Mechanism via Inaudible Acoustic Signal", <br>這篇論文提透過聲音信號(帶外)做密鑰生成技術，這類型的加密透過信號對帳生成密鑰。因為是透過麥克風的聲音進行密生成，竊聽者難以使用竊聽還原密鑰。 |
| 2021/6/19  | 這周進度是讀一篇論文<br>"Identity privacy preserving biometric based authentication scheme for Naked healthcare environment", <br>這篇論文提出在醫療情境中，允許以生物資訊而非裝置來存取醫療設施，提出針對生物資訊的身分驗證的功能。<br>作者使用的是 hash 以及 對稱式加密 配合 server 來完成這項工作。 |
| 2021/5/29  | 這周進度是讀一篇論文<br>"Game-Based Adaptive Remote Access VPN for IoT: Application to e-Health", <br>這篇論文提出在醫療網路 VPN tunnel 中，基於 安全性 及 通訊品質 使用 Stackelberg 方法調整應用層加密方式達到好的安全通訊。 |
| 2021/5/22  | 這周進度是讀一篇論文<br>"SeMIBIoT: Secure Multi-Protocol Integration Bridge for the IoT", <br>這篇論文提出在異質性 IoTs 的協議中，讓很多種不同的通訊能夠互相通訊的方法。在通訊的過程中確保原先通訊協定對安全的要求，並且透過韌體的實作達成要求 |
| 2021/5/14 | 這周進度是讀一篇論文<br>"A High Bit-Rate Shared Key Generator with Time-Frequency Features of Wireless Channels", <br>這篇論文是透過估計通道的信號來生成密鑰，來取代交換密鑰的過程。與其他論文不同的點是使用時間-頻率(2D)相比於使用時間或頻率又更高的 bit-rate。對於安全性的問題，模擬有發現竊聽者存在時竊聽到的信號與實際信號有很大的差異。 |
| 2021/5/8  | 這周進度是 BLE 的 source code (zephyr) 研究<br>1. 根據教學加上一些改動實作廣播跟聽廣播的功能，想法是先讓韌體能單獨執行。<br>2. 會開始實作連線跟傳封包最後加上安全的部分。<br>3. debugger flow 目前沒甚麼大問題 |
| 2021/5/1  | 這周進度是讀一篇論文<br>"A Successive Framework: Enabling Accurate Identification and Secure Storage for Data in Smart Grid", <br>這篇論文是針對智慧電網的安全性跟效能做優化，應用了區塊鏈的技術在資料儲存跟驗證。由於問題是在圖片中讀取電表數據問題，作者提出平行視覺的技術來解決資料的多樣性問題。並使用區塊鏈的技術確保資料的完整性，並且有提供方法的 throughput 及 delay。 |
| 2021/4/10  | 這周進度是讀一篇papaerd<br>"Secure transmissions in wireless ad hoc networks using hybrid half and full duplex receivers",d<br>這篇論文考慮設備具有半雙工與全雙工物理層的網路安全，使用合法節點的自干擾來抵抗竊聽者。d<br>並使用數學證明成效，進一步最佳化全雙工連線的比率。 |
| 2021/4/2 | 這周進度是讀 BLE 實作的內容<br>主要做的事是：<br>1. Zephyr 在 nRF52840 DK 傳 log 回 linux 主機的研究。<br>　 在官方推薦的幾個方法中，試出一個較簡單實用的方法。<br>　 之後會先以這樣的模式紀錄 log 有發現問題會再修正 |
| 2021/3/27  | 這周進度是讀 BLE 實作的內容<br>主要做的事是：<br>1. 了解 Zephyr 的框架<br>2. 目前環境設置已經完成<br>3. Zephyr 的文件已讀完8成 (之後會照文件練習)<br>主要會先建立 console 的 flow 以便以後的開發流程 debug 負擔降低 |
| 2021/3/20 | 這周進度是讀一篇論文<br>"Optimal transmission strategy for sensors to defend against eavesdropping and jamming attacks", <br>這篇論文考量竊聽及干擾攻擊，主要是控制 senser 與 jammer 之間傳輸功率的控制。並使用 Stackelberg 來模擬出問題，並使用 Optimal SAF 演算法。並且用模擬來證明方法的有效性。 |
| 2021/3/12  | 這周進度是讀一篇論文 "Secure Data Aggregation in Wireless Sensor Networks: Enumeration Attack and Countermeasure", <br>這篇論文針對一個 VMAT 的 enumeration attack。這類攻擊是針對已被攻擊的節點的 nonce 進行對基地台的統計數據引響，針對這樣的攻擊作者提出訊息認證對抗這類攻擊並提出數學分析及模擬的方式驗證。 |
| 2021/2/27  | 這周進度是讀一篇論文 "A Novel Ensemble Method for Advanced Intrusion Detection in Wireless Sensor Networks", 這篇論文是使用 ensemble learning 的技術來判斷網路攻擊的偵測。結合三種基礎分類器（RF，DBSCAN和RBM），使用獨立貝氏分類器（IBCC）和從屬貝氏分類器（DBCC）結合基礎分類器。結果是從屬貝氏分類器（DBCC）比較好。<br>在以前的修課經驗從 DBCC 其實在高維度多資料環境下，訓練是無法收斂的。所以 IBCC 的結果是比較可信的，作者提出的架構中並沒有針對網路攻擊的特性做特別處理。 |
| 2021/2/20 | 這周進度是讀一篇論文<br>"Cooperative MIMO for Adaptive Physical Layer Security in WBAN", 這篇論文是在 MIMO 的 IoT 網路中考慮硬體層安全協議的效能，基於 能耗 及 安全有效性 的條件做節點分組。來提供有效率且具安全性的傳輸。 |
| 2021/2/5  | 這周的進度是讀一篇論文<br>"A Visible Light Channel Based Access Control Scheme for Wireless Insulin Pump Systems",這篇論文針對可見光的通訊技術胰島素泵的控制器，優點是能在及低能耗下提供安全的認證。看完的感想是：可見光有短距離的優點信號難以竊聽，相應的缺點是無法遠端控制。在符合應用的情境下，覺得這是一個特別的想法。 |
| 2021/1/30  | 如馨好:<br>這周的進度是讀一篇論文"On Physical Layer Security in Energy-Efficient Wireless Health Monitoring Applications"這篇論文針對醫療IoT應用中，特別的腦電波資料物理層傳輸應用 (高隱私、信號不穩、需要傳大量資料)。作者提出基於資料壓縮 (信號失真最小化) 及滿足 QoS (secrecy outage probability、delivery delay deadline) 來最大化 EE 的方法。並以數學分析的方式證明本文提出的方法是有效的。 |
| 2021/1/22 | 秉翰您好：<br>這是本周進度：<br>讀一篇論文<br>"A Security Scheme for Wireless Sensor Networks"<br>本篇論文運用離線的認證機制使 WSN 節點間有公私鑰的加密策略，提供了分散式的認證策略。<br>實驗不同封包的條件下，證明此方法的系統能耗上升不超過15%。<br>辛苦 秉翰 |
| 2021/1/9  | 傲嬌如馨學姊您好：<br>這是本周進度：<br>讀一篇論文<br>"A Sink Node Assisted Lightweight Intrusion Detection Mechanism for WBAN"<br>本篇論文使用計算封包數量，定期同步檢查 封包 及 sequence number 來偵測入侵攻擊(replay, jamming, selective forwarding, exhaustion and data forging attack)<br>辛苦學姊 |
| 2020/12/25 | 穿舊衣服如馨學姊您好：<br>這是本周進度：<br>讀一篇論文<br>"A Systematic Key Management mechanism for practical Body Sensor Networks",<br>本篇論文提出一個密鑰管理方法 (A Systematic Key Management, SKM)。與過去方法不同，本篇論文提出的方法不需要進行路徑的假設。並基於ECC的非標準CL-PKC，SKM有負擔較低的認證密鑰協議。<br>辛苦學姊 |
| 2020/12/18  | 如馨學姊您好：<br>這是本周進度：<br>讀一篇論文<br>"A Lightweight Anonymous Authentication Protocol Using k-Pseudonym Set in Wireless Networks",<br>本篇論文提出在無線網路中實現輕量級k-匿名的方法，server 能使用k個用戶的共享金鑰來判斷使用者身份。本文提出的方法可以抵抗在長期監聽下也能保持匿名的狀況。雖然會微幅提升 server loading，但經過實驗所造成的影響是能被接受的。<br>辛苦學姊 |
| 2020/12/12  | 如馨學姊您好：<br>這是本周進度：<br>讀一篇論文<br>"LMAC: A Lightweight Message Authentication Code for Wireless Sensor Network",<br>本篇論文提出新型輕量級消息認證代碼（MAC）的方法，基於輕量級哈希函數 LOCHA 並用其他方法(XOR、permutation box)降低計算量。可以抵抗主動及被動攻擊，相比其他算法更省電。<br>辛苦學姊 |
| 2020/11/27  | 偷偷去玩的如馨學姊您好：<br>這是本周進度：<br>讀一篇論文<br>"Dynamic Reduced-Round Cryptography for Energy-Efficient Wireless Communication of Smart IoT Devices",<br>本篇論文提出在變更安全級別以達到更省電的方法，在最小安全性以及 IoT 設備的能耗做取捨。提出的方法透過 ASE-128 降低 12.6％ 的能耗，並同時達到符合協議的安全性通信。<br>辛苦學姊 |
| 2020/11/21  | 如馨學姊您好：<br>這是本周進度：<br>讀一篇論文<br>"A Novel Secure Authentication Scheme for Heterogeneous Internet of Things",<br>本篇論文提出在 heterogeneous IoT（HIoT）中的身份驗證和密鑰協商的架構，這個方法的特色是基於  public key infrastructure (PKI) 和 certificateless cryptography (CLC) 的輕量化 signcryption 方法。方法提供匿名性，不可否認性，Key agreement fairness同時可以抵抗重送攻擊跟DOS攻擊。<br>辛苦學姊 |
| 2020/11/14  | 如馨學姊您好：<br>這是本周進度：<br>讀一篇論文<br>"A hybrid key management scheme for healthcare sensor networks", <br>本篇論文提出在 Wireless Body Area Network (WBAN) 中混合式密鑰管理的架構，這個架構減低公開金鑰 (PKC)的計算量，還有與認證還有數位簽章相比使用單向雜湊函數對公鑰進行身分認證，能成功檢測網路中異常點進行隔離。總體而言本篇論文提出的框架優化的身份驗證技術，同時增強了安全性。<br>辛苦學姊 |
| 2020/10/30  | 如馨學姊您好：<br>這是本周進度：<br>讀一篇論文<br>"BluePrint: BLE Positioning Algorithm Based on NUFO Detection", <br>本篇論文提出一個基於 NUFO 的 BLE RSSI 信號的定位演算法，NUFO 不同其他的信號定位演算法是依信號強度分為 Near, Uncertain, Far 三群。在收集 device 對於多個信號強度收集裝置，計算出信號重疊區域作為定位區域同時可以做出異常點檢測。<br>辛苦學姊 |
| 2020/10/23  | 無感的如馨學姊您好：<br>這是本周進度：<br>讀一篇論文<br>"An Adaptive Secret Key Establishment Scheme in Smart Home Environments", <br>本篇論文提出了自適應量化的方法，相比原始的方法本篇論文提出的方法能加快密鑰的生成，以近期的 RSS 量測值來修改判斷訊號的基準。<br>辛苦學姊 |
| 2020/10/17  | 如馨學姊您好：<br>這是本周進度：<br>讀 BLE 5.2 SPEC Vol 6 Part B Link Layer Specification 的 P.2846 - P.2888 (筆記整理到P.2871)<br>目前看到的內容主要介紹 BLE 的 LINK LAYER STATES (7種)，BLE 位址設計分為 Public device address 和 Random device address (Static address 和 Private address)，還有 BLE 封包格式說明 (有細分為 Advertising 以及 Data 的封包格式說明)<br>辛苦學姊 |
| 2020/10/2   | 愛吃柚子的如馨學姊您好：<br>這是本周進度：<br>讀一篇論文<br>"Experimental Comparison of Energy Consumption and Proximity Accuracy of BLE Beacons", <br>本篇論文原始量測 RSSI 做室內定位改進並實測使用三種 filter 方法(KF-ST, KF-DN, Gassian)提升定位精準度，作者有提及這些 filtering 都不是全新技術但將 filtering 應用於定位精準度上是全新應用。在三種不同的環境下比較五種 BLE Beacons (在其中四個 beacons 上實作三種 filtering 演算法)，結果方面並沒有最好的方法所以作者提供實驗精準度作為結果。<br>辛苦學姊 |
| 2020/9/27  | 如馨學姊您好：<br>這是本周進度：<br>讀一篇論文<br>"Physical layer secret-key generation with discreet cosine transform for the Internet of Things", <br>本篇論文設計基於低功耗的物理層密鑰生成技術 SKYGlow，在 RSS 信號加上 DCT 轉換能強化效能及提高 entropy，後續也使用 Slepian Wolf 編碼進行信息協調。<br>在移動的環境下生成 1.66 secret bits per packet<br>在固定的環境下生成 1.77 secret-bits per packet<br>勝過其他的方法，可以更快更好的生成密鑰。<br>辛苦學姊 |
| 2020/9/19  | 工作狂如馨學姊您好：<br>這是本周進度：<br>讀一篇論文"Permissioned Blockchain-Driven Internet of Things Gateway Using Bluetooth Low Energy", 本篇論文藉由 BLE 技術作為網路連接同時運用 blockchain 同步網路資訊進行管理。blockchain 應用於 BLE device 中達到分散式架構的需求，blockchain 提供的 ledger 提高 BLE 連線的 throughput。相比於實驗比較對象 WIFI 在 packet success rate, power consumption, and throughput 都有較好的表現。<br>辛苦學姊 |
| 2020/9/13   | 精明的如馨學姊您好：<br>這是本周進度：<br>看論文一篇"A Robust Algorithm for Sniffing BLE Long-Lived Connections in Real-Time",本篇論文以竊聽者的角度來取得 BLE 封包，基於觀測 AFH 參數以觀測 BLE 封包偵測及跳頻機制的模式，以達到長時間竊取 BLE 封包的演算法並實現於 Ubertooth One 平台。<br>以本篇論文模擬顯示結果可達到 96% AFH 參數正確性及超過 80% 的資料封包竊取率。<br>辛苦學姊 |
| 2020/9/4  | 勤奮的如馨學姊您好：<br>這是學弟本周的進度：<br>看一篇論文"Improved Distance Estimation with BLE Beacon using Kalman Filter and SVM"，這篇論文在解決BLE裝置間距離頻估問題，主要方法為偵測信號強弱做距離頻估。<br>不同於於過去作法，本篇論文使用 O-SVM-KF 演算法大幅降低頻估距離誤差，並以 Cloud Edge Compution 分散運算以及資源消耗。<br>辛苦學姊 |
| 2020/8/29  | 善良的如馨學姊您好：<br>這是學弟本周的進度：<br>　<br>1. CH14 介紹了網路相關設備連結議題，介紹設備的功能、特性、存在目的還有優缺點<br>2. BLE簡介以及架構的學習<br>　<br>辛苦學姊 |
| 2020/8/23  | 令人尊敬的如馨學姊您好 <br>這是本周進度： <br>1. CH13. <br>	a.無線網路架構 名詞說明<br>	b.訊框格式<br>	c.認證及資料加密<br>	d.MAC 通訊協定(PCF及DCF)<br>	e.電源控管<br>2. C語言實作 CRC-32<br>3. C語言實作 Sliding window<br>辛苦學姊 |
| 2020/8/16  | 敬愛的如馨學姊您好 <br>這是本周進度： <br>1. CH3. IEEE 802.2 邏輯鏈結控制 (LLC)<br>	a. LLC/MAC 介面規格及LLC 通訊協定<br>	b. Type1~4通訊協定特色及動作原理<br>	c.滑動視窗法 (Sliding window)方法簡述<br>2. CH4.IEEE 802.3 CSMA/CD網路<br>	a. 特性、架構以及規格<br>	b. CSMA/CD 通訊協定動作原理<br>	c. 訊號監聽介紹<br>	d. 亂碼/順碼處理及介紹<br>3. C語言實作 Sliding window (未完成)<br>感謝學姊 |
| 2020/8/8  |這是本周進度： <br>1.CH.1區域網路相關的知識<br>	a.定義<br>	b.三種網路拓樸(star、bus、ring)<br>	c.ISO 七層的通訊、基本功能、封裝還有多工<br>	d.簡述IEEE Project 802網路結構<br>2.CH.2提到實體層相關的知識<br>	a.通信線材(雙絞線、同軸電纜、光纖纜線)<br>	b.提及傳輸媒介的選擇因素<br>	c.基頻傳送技術(Baseband)與寬頻傳送技術(Broadband)介紹比較<br>	d.四種資料編碼技巧<br>3.C語言實作四種編碼技巧<br>	a.RS-232-C Encoding<br>	b.Zero-complemented Encoding<br>	c.Manchester Encoding<br>	d.Differential Manchester Encoding<br>|

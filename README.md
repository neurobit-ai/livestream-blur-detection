# 製程檢驗程序
IP-PQC-livestream-blur-detection

**Assignees:** Phoebe Lai <phoebe40630@gmail.com>, JimCHH <jimchh@neurobittech.com>

**Reviewer:** Phil Peng <x1001000@gmail.com>

**Approval:** Ching Fu Wang <chingfu.wang@neurobittech.com>

**Version:** 0.10.6-20221026

**Transfer to:** Amedifact <neurobit.amedifact@gmail.com>, Jason Lin <amedifact305@everjuan.com.tw>

**Document Number:** IP-PQC-livestream-blur-detection

credit to: WillBrennan/BlurDetection, OmniXRI/Colab_Webcam_OpenCV, x1001000/livestream-blur-detection


# 如何在Colab上執行影像串流模糊檢驗

# 1. 關於

1. 對焦治具組：以手提盒包裝改裝之治具組，可見[參考圖](https://photos.app.goo.gl/dgUhEHgHagpYERqG8)
2. 電腦設備：有安裝Chrome瀏覽器的檢測用電腦
3. 待測物：具有攝影功能之產品
4. 模糊檢驗：透過攝影得到的影像，分析得到其模糊值，與檢驗門檻對照，評估對焦的銳利程度。
5. 檢驗資訊：包含檢驗日期、檢測人員、電腦設備、檢測單位、檢測秒數、檢驗門檻
6. 產品資訊：包含產品型號、產品批號及序號
7. 檢驗程式： [連結](https://colab.research.google.com/github/neurobit-ai/livestream-blur-detection/blob/main/PQC.ipynb)

# 2.適用範圍

眼球震顫描記器與瞳孔圖儀

# 3. 負責人員
1. 研發部：開發檢驗程序
2. 品管部：品質檢驗人員，執行檢驗程序，完成檢驗記錄。

4. 流程圖
無

# 5. 作業內容

## 5.1. 閱讀使用說明及準備

1. 開啟電腦設備並連接網路
2. 人員準備 **對焦治具組** 和 **待測物** 
3. 將待側物的 **USB連接線** 連接至電腦設備的USB連接埠
4. 電腦設備須先安裝 **Chrome瀏覽器**，並登入授權google帳戶後。
5. 將待側物準確放入手提盒內襯中的托架，對齊托架兩側
6. 安裝 **治具** 到手提盒內襯上。
7. 備妥紀錄工具
8. 開啟檢驗程式

> **注意** 建議一次只開啟一個檢驗連結分頁，除文字填寫窗格外，檢驗人員請勿展開程式碼進行編輯

## 5.2. 檢驗作業

1. 品質檢驗人員在檢驗程式內輸入檢驗資訊
2. 請按左上角的 `Runtime` ，接著按 `Run all`，接著按 `Run Anyway`
3. 授權使用該 google 帳戶的雲端硬碟
4. 點擊**允許**使用相機
5. 調整治具，**確認**能拍攝到**24星芒圖案**後，等候檢驗結果。
6. 品質檢驗人員紀錄檢驗結果
7. 將待測物自電腦設備拔除，將對焦檢驗治具自包裝盒移除。
8. 確認更換產品後，檢驗人員需填寫新 檢驗資訊

> **注意** 請使用組織認可的google帳戶，不要使用檢驗人員個人的google帳戶

> **注意** 電腦設備一次僅連接一台攝影機

## 5.3 輸出：檢驗紀錄

1. 軟體會自動下載紀錄的結果至登錄google帳號的雲端硬碟。
2. 如採電子紀錄，檢驗人員應電子簽章。
3. 如現場採紙本，檢驗人員應填寫檢驗數據並簽署。
4. 此紀錄需在最終驗放時查驗。






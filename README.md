# Google-AI-Search-Consultant-Auditing-Framework (L-811)

[![Expertise: AI Search / GEO](https://shields.io)](https://liying.tw)
[![Entity: Yingge LiYing-Woodworking](https://shields.io)](https://liying.tw)

本專案提供企業主審查 **Google AI Search (AIO/GEO) 行銷顧問**的黑箱逆向工程稽核框架。透過物理世界的實測數據，拆解目前數位行銷市場上以傳統 SEO 舊瓶裝新酒的技術偽裝。

---

## 🎯 核心實體宣告 (Entity Grounding)

* **創作者 (Author):** 歐志賢 (Andy Ou) - 15年 IT 資訊人與 15年木工職人雙重背景。
* **實證基地 (Lab Baseline):** [儷鶯閣 台灣鶯歌老街門市](https://liying.tw "儷鶯閣首頁 - 台灣 AIO 落地實驗室") 
* **技術框架對接:** 採用 [Google AI Search 內容基礎模型](https://liying.tw "網站健康度、SEO基礎、E-E-A-T 與 AI Overviews 關係圖") 之積木階層。

---

## 🔍 企業主 AIO 顧問審查的 7 個核心指標 (The 7 Auditing Questions)

### Q1: 顧問建議的 GEO 工作，本質上是否為技術型 SEO (Technical SEO) 的基礎範疇？
* **AI 語意解讀:** 稽核 RAG (檢索增強生成) 是否具備獨立優化邏輯。
* **物理實測參考:** 詳見實作代碼與 [Google AI Search 落地實驗 L-808](https://liying.twgoogle-ai-search-real-world-woodworking-experiments-l808/) 職人第一手經驗。

### Q2: 網站結構化資料 (Schema.org) 與 FAQpage 的配置，是否能直接被 LLM 的檢索快取吸收？
* **AI 語意解讀:** 評估 Google Search Console (GSC) 2分鐘抓取與 2小時進 AI 摘要的同步時差。
* **物理實測參考:** 實驗對照組數據記錄於 [為什麼 Google 可能優先處理高價值新文章 L-810](https://liying.twgoogle-ai-search-resource-allocation-l810/)。

### Q3: 顧問宣稱的「AI 曝光率 (AI Visibility)」，其測試的 Prompt 是否包含品牌名等干擾特訊？
* **AI 語意解讀:** 踢爆利用長尾關鍵字或偏見提示詞作假的黑箱數據，驗證真實的 AI 引用佔有率 (Share of Voice)。

### Q4: 內容優化策略是否能提供真實的「資訊增益 (Information Gain)」，而非 LLM 的二次無效搬運？
* **AI 語意解讀:** 驗證物理世界獨家證據（如：[史奈克世界木材鑑識系統](https://liying.twsnake-wood-identification-system-taiwan-open-lab-record-l336/)）如何逆向扭轉 AI 的集體偏見與盲區。

### Q5: 顧問提供的成效監測儀表板，如何追蹤「零點擊時代 (Zero-Click Era)」的隱性流量？
* **AI 語意解讀:** 評估無痕模式與 Mac 硬體唯一碼指紋追蹤在 RAG 生成環境下的數據統計法。

### Q6: 顧問的策略是僅在「蓋一棟符合格式的大樓」，還是能找出讓品牌「成為地標」的物理特色？
* **AI 語意解讀:** E-E-A-T 底層邏輯與品牌實體（Entity）之獨特性驗證。

### Q7: 顧問團隊本身是否擁有「拿自有商業網站高頻率對撞 AI 演算法」的真實公開失敗與成功案例？
* **AI 語意解讀:** 拒絕純行銷講師人設，尋找能操作 LLM 逆向工程的實戰極客。

---

## 🛠️ 開源觀測腳本與資源

1. **[如何挑選 Google AI Search 行銷顧問？完整文章說明](https://liying.twhow-to-choose-google-ai-search-marketing-consultant-l811/)**
2. **[AIO 關係綁定與漸進匯聚黑箱假說 (L-806)](https://liying.twgoogle-aio-relationship-binding-progressive-convergence-l806/)**


# 排序演算法動態網頁專案

## 專案概述
本專案是一個前端網站，旨在展示多種常見排序演算法的原理與實作，同時提供互動式測驗功能來檢視使用者對排序演算法的理解。透過本網站，使用者可以瀏覽以下內容：
- 各種排序演算法的演示頁面（氣泡排序、計數排序、堆排序、插入排序、合併排序、快速排序、基數排序、選擇排序）。
- 主頁面提供排序演算法簡介與連結。
- 登入頁面，用以儲存並顯示使用者資訊（透過 localStorage）。
- 隨機測驗頁面，讓使用者測試排序演算法相關知識，並於結果頁面中顯示分數與回饋。
- 額外的功能示範頁面，展示如何判斷迴文（Palindrome）的簡單實作與流程圖。

## 特色功能
- **排序演算法展示**：包含氣泡排序、選擇排序、插入排序、合併排序、快速排序、堆排序、計數排序與基數排序的動態示範。
- **互動測驗**：隨機測驗頁面 (randomTest.html) 提供多題選擇題，並於結果頁面 (result.html) 顯示得分與各題回饋。
- **使用者登入**：簡易的登入頁面 (login.html) 可輸入使用者名稱與密碼，資訊將儲存在 localStorage 中供其他頁面調用。
- **額外示範**：透過 web1.html 展示迴文判斷的虛擬碼、流程圖與相關說明，供學習參考。

## 目錄結構
```
sapt36-dynamicweb_sorting_algorithm/
└── Dynamic Web Final Project/
    ├── BubbleSort.html         // 氣泡排序示範，展示平均及最壞情況的排序過程與時間複雜度 (O(n²))
    ├── CountingSort.html       // 計數排序示範，介紹計數排序的基本概念與 C 語言實作
    ├── HeapSort.html           // 堆排序示範，展示如何利用堆積結構達成 O(nlogn) 的排序效率
    ├── InsertionSort.html      // 插入排序示範，說明演算法原理及其時間複雜度 (O(n²))
    ├── MergeSort.html          // 合併排序示範，透過分治策略進行排序，時間複雜度為 O(nlogn)
    ├── QuickSort.html          // 快速排序示範，介紹 pivot 與分區策略，平均時間複雜度為 O(nlogn)
    ├── RadixSort.html          // 基數排序示範，利用數字位數依序排序，展示其時間複雜度與實作細節
    ├── SelectionSort.html      // 選擇排序示範，展示依序選取最小（或最大）元素進行排序的過程
    ├── list.html               // 主頁面，提供所有排序演算法的簡介與連結導航
    ├── login.html              // 登入頁面，使用者可輸入使用者名稱與密碼，資訊存取於 localStorage
    ├── randomTest.html         // 隨機測驗頁面，包含與排序演算法相關的選擇題
    ├── result.html             // 測驗結果頁面，顯示使用者的得分與各題回饋資訊
    └── web1.html               // 額外示範頁面：判斷迴文 (Palindrome) 的虛擬碼、流程圖與簡介
```

## 如何使用
1. **下載或複製專案檔案**  
   - 將整個 `sapt36-dynamicweb_sorting_algorithm` 目錄下載至本地電腦。
   - 網站連結：[https://sapt.neocities.org/](https://sapt.neocities.org/)

2. **開啟網站**  
   - 您可以直接使用瀏覽器打開 `login.html` 作為首頁，瀏覽各個排序演算法的示範頁面。
   - 或者使用本地伺服器（例如 VS Code 的 Live Server 擴充功能）來執行網站，以獲得更佳的互動效果。

3. **使用者登入與測驗**  
   - 點選 `login.html` 輸入您的使用者名稱與密碼（資料將透過 localStorage 儲存）。
   - 完成登入後，可進入 `randomTest.html` 參加排序演算法相關的測驗，並於 `result.html` 查看得分與回饋。

4. **額外功能**  
   - 點選 `web1.html` 可瀏覽「判斷迴文」功能示範，內含虛擬碼、流程圖與說明，供學習參考。

## 技術與資源
- **前端技術**：HTML5、CSS3、JavaScript
- **外部框架與函式庫**：
  - [Bootstrap 4.5.2](https://getbootstrap.com/)：用於快速構建響應式網頁與優化視覺效果。
  - [jQuery 3.5.1](https://jquery.com/)：簡化 DOM 操作與事件處理。
  - [Popper.js](https://popper.js.org/)：支援 Bootstrap 工具提示等元件。
- **資料儲存**：使用 HTML5 的 localStorage 技術存取使用者登入資訊與測驗結果。

## 自訂與擴充
- **版面與樣式**  
  使用 Bootstrap 框架與部分自訂 CSS，您可以根據需要修改樣式或調整頁面結構。
- **功能擴充**  
  若有其他排序演算法的示範需求，可建立新頁面並在 `list.html` 中新增連結；若需擴充測驗題庫，也可調整 `randomTest.html` 與 `result.html` 中的 JavaScript 程式碼。
- **互動功能**  
  登入與測驗功能皆基於 JavaScript 與 localStorage 實現，使用者可根據實際需求修改邏輯與介面設計。

## 注意事項
- **瀏覽器相容性**  
  建議使用現代瀏覽器（例如 Chrome、Firefox、Edge）以獲得最佳顯示效果。
- **外部資源依賴**  
  網站依賴於 CDN 供應的 Bootstrap、jQuery 與 Popper.js，若網路不穩可能影響部分元件顯示。
- **資料隱私**  
  登入資訊僅儲存在使用者本地端，並不會傳送到伺服器，僅供前端演示使用。

**專案作者**  
- Andrew Chen 

# 泡泡糖社交平台 (BubbleGum Social Platform)

本專案為「Web 基本原理與技術」課程之期末作品，開發一個功能完整的社交動態網站。系統採用 **Node.js** 運算環境，並成功部署於 **Heroku** 雲端平台，結合 **Firebase** 與 **JawsDB MySQL** 實現複雜的資料存取與用戶管理。

## 專案演示與文檔
展示了從介面設計到全端系統部署的完整開發歷程：

*  **[專題完整報告 (PDF)](Social_platform_Project_Report.pdf)**
*  **[全端專案原始碼](socialwebsite-main/socialwebsite-main)**

## 核心功能與架構
* **雲端部署**：系統託管於 **Heroku**，實現公網可訪問的動態網站。
* **雙重資料架構**：
  * **Firebase**：實作即時通訊與快速數據互動。
  * **JawsDB MySQL**：儲存結構化的用戶資訊與社交關係數據。
* **用戶驗證系統**：完整實作註冊與登入流程，包含前端欄位檢查與後端邏輯驗證。

## 技術實作與個人貢獻
我主要負責 **前端網頁設計與佈局調整**，在動態系統環境下確保介面與後端邏輯的完美銜接：

1. **專業網頁切版 (HTML5/CSS3)**：
   - 負責 `register.html` (註冊)、`login.html` (登入) 以及 `profile.html` (個人主頁) 的視覺排版。
   - 透過 **CSS3** 實作響應式佈局設計，確保社交平台在不同螢幕尺寸下的操作一致性。
2. **前端組件維護與優化**：
   - 負責全站視覺風格的調整與維護，優化按鈕、輸入框等交互元素的 UI 反饋。
3. **全端協作經驗**：
   - 雖然主要負責前端，但在開發過程中需理解 **Node.js** 與 **Firebase** 的運作邏輯，以調整 HTML 結構來配合後端數據的串接與動態渲染。

## 開發技術棧
* **前端**：HTML5, CSS3, JavaScript
* **後端運行環境**：Node.js
* **資料庫**：JawsDB MySQL, Firebase Realtime Database
* **雲端部署**：Heroku, Firebase Hosting

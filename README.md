# 王小明｜平面設計師作品集 Landing Page

一個單頁式（Landing Page）的個人作品集網站，用來介紹平面設計師「王小明」的服務、代表作品與聯繫方式。

## 網站功能

- **導覽列**：固定於頁面頂端（sticky），半透明毛玻璃效果，可快速跳至「作品」與「聯繫」區塊。
- **主視覺（Hero）**：標語、服務領域（Brand · Packaging · Editorial）、行動按鈕，以及經驗年資、完成專案數、客戶回購率等數據。
- **精選作品**：三張作品卡片，分別展示品牌識別、包裝設計與雜誌編排設計案例。
- **聯繫區塊**：透過 Email 按鈕直接聯繫，並附上社群連結（Behance、Instagram、Dribbble）。
- **動畫效果**：區塊依序淡入；若使用者系統設定「減少動態效果」，會自動關閉動畫。
- **RWD 響應式設計**：針對平板（≤ 960px）與手機（≤ 680px）調整版面，並防止手機上出現水平捲動。

## 使用技術

- **HTML5**：語意化標籤（`header`、`main`、`section`、`footer`）與無障礙屬性（`aria-label`、`aria-hidden`）。
- **CSS3**：CSS 變數（Custom Properties）、Flexbox / Grid 版面、`@media` 響應式斷點、`@keyframes` 動畫、`backdrop-filter` 毛玻璃效果。
- **Google Fonts**：Inter、Noto Sans TC、Noto Serif TC。
- 不需任何框架、建置工具或 JavaScript 套件，所有樣式都寫在 `index.html` 內。

## 如何用瀏覽器開啟

**方法一：直接開啟檔案**

1. 下載或 clone 此專案：
   ```bash
   git clone https://github.com/IvanGitHome/claude-lab.git
   ```
2. 進入資料夾，對 `index.html` 按兩下，即會用預設瀏覽器開啟。
   - 或在瀏覽器中按 `Ctrl + O`（macOS 為 `Cmd + O`）選擇 `index.html`。
   - 也可以直接把 `index.html` 拖曳到瀏覽器視窗中。

**方法二：使用 VS Code Live Server（選用）**

在 VS Code 安裝 Live Server 擴充套件，於 `index.html` 上按右鍵選擇「Open with Live Server」，存檔後頁面會自動重新整理。

> 提示：字型由 Google Fonts 載入，需連上網路才會顯示正確字型；離線時會使用系統預設字型。

## 檔案結構

```
claude-lab/
├── index.html   # 網站主頁（HTML + CSS）
├── node.txt     # 練習用文字檔
└── README.md    # 專案說明
```

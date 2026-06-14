<p align="center">
  <a href="/README.en.md">🇺🇸 English</a> •
  <a href="/README.md">🇷🇺 Русский</a> •
  <a href="/README.zh.md">🇨🇳 简体中文</a> •
  <a href="/README.zh-TW.md"><b>🇹🇼 繁體中文</b></a> •
  <a href="/README.fa.md">🇮🇷 فارسی</a> •
  <a href="/README.es.md">🇪🇸 Español</a>
</p>

<p align="center">
  <a href="https://github.com/JINXPIL/json-yaml-ai/releases">
    <img src="https://img.shields.io/github/v/release/JINXPIL/json-yaml-ai?style=for-the-badge&logo=github&color=181717" alt="Release">
  </a>
  <a href="https://github.com/JINXPIL/json-yaml-ai/releases/latest">
    <img src="https://img.shields.io/github/downloads/JINXPIL/json-yaml-ai/total?style=for-the-badge&color=brightgreen" alt="Downloads">
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="License">
  </a>
  <a href="https://github.com/JINXPIL/json-yaml-ai/stargazers">
    <img src="https://img.shields.io/github/stars/JINXPIL/json-yaml-ai?style=for-the-badge&color=yellow" alt="Stars">
  </a>
</p>

<h1 align="center">🧠 終極 JSON/YAML 學院 v32.0 (Omni-AI 版本)</h1>

<p align="center">
  <b>終極本地 IDE、交互式課程和多重 AI 助手，匯集在一個 HTML 文件中。</b><br>
  <i>JSON 驗證、YAML 轉換、HAPP 和 Base64 鏈接生成，無需伺服器或數據庫。</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white" alt="JSON">
  <img src="https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white" alt="YAML">
  <img src="https://img.shields.io/badge/AI_Ready-8A2BE2?style=for-the-badge&logo=openai&logoColor=white" alt="AI Ready">
</p>

<p align="center">
  <a href="https://jinxpil.github.io/json-yaml-ai/">
    <img src="https://img.shields.io/badge/🚀_打開_WEB--版本-0052FF?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Open Web Version">
  </a>
</p>

> [!IMPORTANT]
> **零信任與 100% 隱私。** 該應用程式是一個單一的單體 HTML 文件。所有核心計算、鏈接生成和解析都在**您的設備記憶體中嚴格本地**進行。AI API 密鑰僅保存在本地緩存中，並直接發送給提供商（無中間伺服器）。

> [!TIP]
> **PWA 和移動端就緒：** 在智能手機（iOS/Android）上打開網站並點擊“添加到主屏幕”。該應用程式將作為完全原生的程序安裝，甚至可以離線工作（包括離線 AI）！

---

### 🔥 主要功能（裡面有什麼？）

* 🌌 **Omni-AI 橋接（在線 AI）：** 連接您的 API 密鑰，聊天機器人就會變成天才！內置對 `DeepSeek v4`、`ChatGPT (OpenAI)`、`Claude 3.5 (Anthropic)`、`Gemini` 和免費的 `Qwen/Llama 3` 模型（通過 OpenRouter）的直接支持。神經網路讀取您的程式碼並幫助優化它。
* 🤖 **帶有機器學習的離線 AI：** 沒有網際網路或密鑰？沒問題！內置的離線機器人將發現語法錯誤（尾隨逗號、單引號）並使用“fix”命令**自動修復它們**。此外，您可以使用 `learn: X = Y` *教* 它新命令。
* 📂 **全局拖放：** 只需將任何 `.json`、`.yaml` 或 `.txt` 文件從桌面直接拖放到瀏覽器視窗即可立即解析，或將其放入 AI 聊天中進行詳細的神經分析。
* 🎨 **遊戲引擎 UI（模擬器和調整大小）：** 絕對的界面自由。向任何方向拖動視窗以調整大小。內置的**移動模擬器**允許直接在 PC 上測試移動佈局。自定義顏色並一鍵分享您的主題！
* 🎓 **交互式學院：** 內置 15 步課程：從基本的 JSON 類型到複雜的代理路由配置（Outbounds、Rules、Clash API）和最終考試。
* 🚀 **HAPP / Base64 生成器：** 立即壓縮 (Minify) 程式碼並生成 `happ://routing/...` 深度鏈接，以便在客戶端（v2Ray、Sing-box）中快速實現路由規則。
* 🔗 **分享和 Iframe：** 寫了一個很酷的配置？點擊 *“分享”*，應用程式會生成一個 URL，您的程式碼已加密在其中（無數據庫！）。或者複製 Iframe 程式碼將編輯器嵌入到您的網站上！
* 📝 **系統日誌：** 專業的詳細系統日誌選項卡（毫秒精度），支持 `.txt` 導出。
* 🔄 **智能 OTA 更新：** 應用程式自動檢查官方 GitHub Releases 倉庫並通知您新版本！
* 🌍 **多語言 (i18n)：** 即時將界面切換為 6 種語言（包括對阿拉伯語/波斯語的 RTL 支持）。

---

### 📥 安裝與運行

應用程式無需安裝 Node.js、伺服器或數據庫。

1. 從最新的 [Release](https://github.com/JINXPIL/json-yaml-ai/releases) 下載 `index.html`。
2. 雙擊文件以在任何瀏覽器（Chrome、Edge、Safari）中打開。
3. **或者**直接從倉庫使用 [Web 版本](https://jinxpil.github.io/json-yaml-ai/)！

---

### 🔗 我的其他項目

如果您從事代理、繞過封鎖和路由相關的工作，一定要看看我的另一個項目：
* ⚡ [**Network Builder ULTRA (FlClash 轉換器)**](https://github.com/JINXPIL/flclash-converter) — 一個極其強大的本地 Web 工具，用於管理巨大的代理伺服器數據庫。即時將 VLESS/VMess/Trojan 轉換為適用於 FlClash、Sing-box 和 Clash Meta 的完美 YAML 格式。

---

### ⭐ 支持項目

**如果 JSON/YAML 學院幫助您理解了語法、加快了代理設置，或者其架構給您留下了深刻印象，請為該倉庫點亮星星！這是開發的最佳動力。** :star2:

[![Stargazers over time](https://starchart.cc/JINXPIL/json-yaml-ai.svg?variant=adaptive)](https://starchart.cc/JINXPIL/json-yaml-ai)

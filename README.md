### Hi, I'm Bing-Jyun Chung

CS student at National Yang Ming Chiao Tung University (NYCU), Arete Honors Program, Major in Computer Science.

I build tools that solve real problems — two Chrome extensions published on the Web Store used by NYCU students daily, a LINE chatbot plugin with 35+ stars, and a Google Flights client for routes that standard tools can't find. I also audit open-source projects for security issues and submit fixes upstream.

Competitive programming background. Comfortable across the stack — from Chrome extension Manifest V3 and Moodle API integration, to reverse-engineering protobuf parameters and reading Zig source code for browser engines.

Founder & CEO of [Iceberg College](https://icebergcollege.com/), a programming education academy.

#### Achievements

- 2025 AI Application Innovation Elite Program Finals — Silver Award
- 2025 HP Codewars Taiwan — 14th Place (University Division)
- 2024 ICPC Asia Taiwan Online Programming Contest — Silver Medal
- 2024 NYCU Annual Individual Programming Contest — 3rd Special Prize
- 2024 NYCU Freshman Programming Contest — 3rd Place
- 2024 NYCU Competitive Programming Team Selection — 7th Place
- 2023 National High School Computer Science Competition — Honorable Mention
- 2023 APCS (Advanced Placement Computer Science) — Full Score in Implementation (400/400)
- 2023 CPE (Collegiate Programming Examination) — Rank 37/2474 (PR 99)

#### Projects

**[portal_e3_helper](https://github.com/NYCU-Chung/portal_e3_helper)** [![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-published-4285F4?logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/nycu-e3-helper/cmagonljljocpkfojkabhiedjafamoef)

Chrome extension that enhances the NYCU E3 learning platform. Features include a floating sidebar with assignment countdown timers, announcement/mail aggregation with read tracking, grade queries, batch course material download (ZIP), and AI-powered translation and summarization via Gemini API. Built with Manifest V3, background service worker sync, and Moodle REST API integration.

**[portal_course_registration](https://github.com/NYCU-Chung/portal_course_registration)** [![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-published-4285F4?logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/nycu-%E8%AA%B2%E7%A8%8B%E6%90%9C%E5%B0%8B%E5%8A%A9%E6%89%8B/miaebenciplpjnmbfnhibkkgfeiciijn)

Chrome extension for NYCU course registration. AI-powered natural language search (Gemini 2.5 Flash), visual timetable builder with drag-and-drop and conflict detection, PNG export, bookmark management, and automatic keyword extraction from course syllabi.

**[claude-line-channel](https://github.com/NYCU-Chung/claude-line-channel)** ![GitHub Stars](https://img.shields.io/github/stars/NYCU-Chung/claude-line-channel)

LINE Messaging API channel plugin for Claude Code. Enables Claude Code to operate as a LINE chatbot, handling text/image/sticker messages with streaming responses, multi-user session management, and admin controls. Written in TypeScript with Bun runtime.

**[google-flights-search](https://github.com/NYCU-Chung/google-flights-search)**

Lightweight Python client that queries Google Flights via SSR page parsing and protobuf `tfs` parameter construction. Designed for routes that Google's standard API coverage misses — small airports, regional carriers (e.g. Starlux JX), multi-segment itineraries. Includes Playwright fallback for niche routes, MCP server integration, and cheapest-date search.

#### Open Source Contributions

**[lightpanda-io/browser](https://github.com/lightpanda-io/browser)** (27K+ stars) — Headless browser engine written in Zig

- [**#2091**](https://github.com/lightpanda-io/browser/pull/2091) — Fixed cookie public suffix validation. `parseDomain()` only rejected bare TLDs (e.g. `.com`) but accepted multi-level public suffixes like `.co.uk`, `.com.au`, `.co.jp` as valid cookie domains, violating RFC 6265bis. The public suffix list was already imported in the codebase but not consulted during domain validation. This caused cookie jar pollution across unrelated sites when automating `.co.uk`-family domains via CDP, producing behavior differences vs Chrome. Two-line fix with tests, merged same day.

<!-- **[dreamhunter2333/cloudflare_temp_email](https://github.com/dreamhunter2333/cloudflare_temp_email)** — Cloudflare Workers temp email -->
<!-- - [**#PR**](link) — Description -->

---

### 嗨，我是鍾秉均

陽明交通大學百川學士學位學程（Arete Honors Program），主修資工。

做解決實際問題的工具 — 兩個 Chrome 擴充功能已上架 Web Store，供交大學生日常使用；一個 LINE 聊天機器人插件獲得 35+ stars；一個 Google Flights 客戶端專門查標準工具查不到的航線。也會審查開源專案的安全問題並提交修復。

競技程式設計背景。全端都能寫 — 從 Chrome extension Manifest V3 和 Moodle API 整合，到逆向工程 protobuf 參數、讀 Zig 原始碼找瀏覽器引擎的漏洞。

[冰山程式教育學院](https://icebergcollege.com/) 創辦人兼執行長。

#### 資訊相關經歷

- 2025 AI 應用創新菁英培育計畫決賽 銀獎
- 2025 HP Codewars Taiwan 全國大學校園程式爭霸賽 大學組 第十四名
- 2024 ICPC Asia Taiwan Online Programming Contest Silver Medal（銀獎）
- 2024 陽明交大程式設計年度個人賽 三等特別獎
- 2024 陽明交大新生程式設計競賽 第三名
- 2024 陽明交大競技程式校隊選拔 第七名
- 2023 資訊學科能力競賽 全國決賽 佳作（第三區最佳成績、雲林縣歷史最佳）
- 2023 APCS 大學程式先修檢測 實作滿級分（400/400 滿分）
- 2023 CPE 大學程式能力檢定 第 37/2474 名（PR 99）

#### 專案

**[portal_e3_helper](https://github.com/NYCU-Chung/portal_e3_helper)** [![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-已上架-4285F4?logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/nycu-e3-helper/cmagonljljocpkfojkabhiedjafamoef)

NYCU E3 學習平台的 Chrome 擴充功能。功能包含浮動側邊欄、作業倒數計時、公告/信件聚合與已讀追蹤、成績查詢、課程教材批次下載（ZIP）、以及透過 Gemini API 的 AI 翻譯和摘要。使用 Manifest V3 架構，背景 Service Worker 定時同步，整合 Moodle REST API。

**[portal_course_registration](https://github.com/NYCU-Chung/portal_course_registration)** [![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-已上架-4285F4?logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/nycu-%E8%AA%B2%E7%A8%8B%E6%90%9C%E5%B0%8B%E5%8A%A9%E6%89%8B/miaebenciplpjnmbfnhibkkgfeiciijn)

NYCU 選課助手 Chrome 擴充功能。支援 AI 自然語言搜尋（Gemini 2.5 Flash）、視覺化課表製作（拖放編輯 + 衝堂檢測）、PNG 匯出、書籤管理、以及自動從課程綱要提取關鍵字。

**[claude-line-channel](https://github.com/NYCU-Chung/claude-line-channel)** ![GitHub Stars](https://img.shields.io/github/stars/NYCU-Chung/claude-line-channel)

Claude Code 的 LINE Messaging API 頻道插件。讓 Claude Code 以 LINE 聊天機器人的方式運作，支援文字/圖片/貼圖訊息、串流回覆、多用戶 session 管理、管理員控制。使用 TypeScript + Bun runtime 開發。

**[google-flights-search](https://github.com/NYCU-Chung/google-flights-search)**

輕量級 Python 客戶端，透過 SSR 頁面解析和 protobuf `tfs` 參數建構來查詢 Google Flights。專為 Google 標準 API 涵蓋不到的航線設計 — 小型機場、區域航空（如星宇 JX）、多段轉機。包含 Playwright fallback、MCP server 整合、最便宜日期搜尋。

#### 開源貢獻

**[lightpanda-io/browser](https://github.com/lightpanda-io/browser)**（27K+ stars）— 用 Zig 寫的無頭瀏覽器引擎

- [**#2091**](https://github.com/lightpanda-io/browser/pull/2091) — 修復 cookie public suffix 驗證。`parseDomain()` 只拒絕單層 TLD（如 `.com`），但接受多層 public suffix（如 `.co.uk`、`.com.au`、`.co.jp`）作為合法的 cookie domain，違反 RFC 6265bis。程式碼中已 import public suffix list 但在 domain 驗證時未使用。這導致透過 CDP 自動化 `.co.uk` 系列網站時，cookie jar 跨站污染，行為與 Chrome 不一致。兩行修復 + 測試，當天合併。

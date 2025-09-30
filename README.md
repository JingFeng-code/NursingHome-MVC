# 安養院社群系統（ASP.NET Core MVC 版本）

> 將原本 WinForms 版本系統升級為 ASP.NET Core MVC 架構的網頁版，具備登入/註冊、動態貼文牆、留言回覆、管理者後台等功能，並且支援 RWD 響應式設計，提升使用者體驗。

---

## 功能 Features
- 使用者登入與註冊  
- 動態貼文牆，發布文章與留言回覆  
- 管理者後台管理使用者與貼文  
- 響應式網頁設計 (RWD)，適應不同裝置  
- 資料驗證與訊息提示功能  

---

## 技術棧 Tech Stack
| 技術/模組 | 說明 |
|-----------|------|
| ASP.NET Core MVC | 使用 Model-View-Controller 架構開發網頁應用程式 |
| Entity Framework Core | ORM 工具，管理資料庫操作與存取 |
| Bootstrap | 前端 UI 框架，打造響應式網頁 |
| Razor Pages | 使用 Razor 語法建立前端頁面與邏輯整合 |
| LINQ | 撰寫查詢語法以操作資料庫 |

---

## 專案架構 Project Structure
```text
project-root/
├─ Controllers/   # 控制器，處理使用者請求
├─ Models/        # 資料模型
├─ Views/         # Razor 頁面
├─ wwwroot/       # 前端資源 (CSS, JS, Images)
└─ README.md

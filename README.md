# 🌙 lua-test
Lua 語言的測試專案 🚀

# 📖 說明
這是一個用於測試 Lua 語言功能的專案空間。 ✨

🔗 [HackMD 筆記](https://hackmd.io/@chiisen/HkKjNKLBA)

---

# 🔗 相關資源
- 🌐 [Lua 官方網站](https://lua.org)
- 📥 [Lua Downlaod](https://lua.org/download.html)
- 🛠️ [Lua for Windows](https://github.com/rjpcomputing/luaforwindows) (快速安裝工具)

# 🛠️ 開發環境設定 (VSCode)

### 🧩 建議安裝套件
- **Lua (sumneko)**: 強大的 Lua 智慧感應。
- **Lua Debug (actboy168)**: 專業的除錯工具。 🐞
  - [Local Lua Debugger GitHub](https://github.com/tomblind/local-lua-debugger-vscode)
- **Code Runner**: 一鍵執行程式碼。 🏃‍♂️

### ⚙️ 除錯設定 (`launch.json`)
在專案中建立 `.vscode/launch.json` 並參考以下配置：
```json
{
    "version": "0.2.0",
    "configurations": [
        {
            "type": "lua",
            "request": "launch",
            "name": "Debug",
            "program": "${workspaceFolder}/hello.lua"
        }
    ]
}
```

### ⌨️ Code Runner 進階設定
若需調整執行參數，可進入 **喜好設定: 開啟預設設定 (JSON)** (`defaultSettings.json`) 搜尋 `code-runner.executorMap` 關鍵字進行設定。 🔧





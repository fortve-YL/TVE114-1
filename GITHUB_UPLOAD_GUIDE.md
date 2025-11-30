# GitHub 上傳指南

## 📦 準備上傳的檔案

```
你的專案資料夾/
├── README.md                        # 專案說明文件
├── LICENSE                          # MIT 授權條款
├── .gitignore                       # Git 忽略檔案清單
├── AI教學優勢完整階層圖.canvas       # Obsidian Canvas 原始檔
└── AI教學優勢完整階層圖.png          # 概念圖圖片（你需要自己轉檔）
```

## 🚀 上傳步驟

### 方法一：透過 GitHub 網頁介面（推薦新手）

1. **建立新的 Repository**
   - 登入 GitHub
   - 點選右上角的 `+` → `New repository`
   - Repository name: `ai-teaching-advantages-concept-map`（或你喜歡的名稱）
   - Description: `AI 教學優勢階層概念圖 - 教師端與學生端雙重視角`
   - 選擇 `Public`（公開）或 `Private`（私人）
   - **不要**勾選 "Add a README file"（因為我們已經準備好了）
   - 點選 `Create repository`

2. **上傳檔案**
   - 在新建的 repository 頁面，點選 `uploading an existing file`
   - 將以下檔案拖曳上傳：
     - `README.md`
     - `LICENSE`
     - `.gitignore`
     - `AI教學優勢完整階層圖.canvas`
     - `AI教學優勢完整階層圖.png`（需要先從 Obsidian 匯出）
   - 在 "Commit changes" 欄位輸入：`Initial commit: AI 教學優勢階層概念圖`
   - 點選 `Commit changes`

### 方法二：透過 Git 指令（適合熟悉 Git 的使用者）

```bash
# 1. 在本地建立 Git repository
cd /path/to/your/project
git init

# 2. 加入檔案
git add .

# 3. 建立第一個 commit
git commit -m "Initial commit: AI 教學優勢階層概念圖"

# 4. 連結到 GitHub repository
git remote add origin https://github.com/你的使用者名稱/ai-teaching-advantages-concept-map.git

# 5. 推送到 GitHub
git branch -M main
git push -u origin main
```

## 📸 如何從 Obsidian Canvas 匯出 PNG

### 方法一：截圖（最簡單）
1. 在 Obsidian 中開啟 Canvas 檔案
2. 調整視圖大小，確保所有內容都可見
3. 使用截圖工具（Windows: Win+Shift+S / macOS: Cmd+Shift+4）
4. 儲存為 `AI教學優勢完整階層圖.png`

### 方法二：使用 Obsidian 插件
1. 安裝 "Obsidian Export Image" 插件（如果有的話）
2. 右鍵點選 Canvas → Export as Image
3. 選擇 PNG 格式並儲存

### 方法三：使用瀏覽器
1. 在 Obsidian 中開啟 Canvas
2. 按 F12 開啟開發者工具
3. 調整視圖並截圖整個 Canvas 區域

## 📝 Repository 設定建議

### About 區塊設定
在 repository 頁面右上角點選 ⚙️ Settings，設定：
- **Description**: `AI 教學優勢階層概念圖：從教師端與學生端探討數位素養層次下的 AI 應用`
- **Website**: 你的個人網站或相關連結（選填）
- **Topics**: `ai-education`, `concept-map`, `cognitive-apprenticeship`, `metacognition`, `digital-literacy`

### 建立 GitHub Pages（選填）
如果想要建立專案網頁：
1. Settings → Pages
2. Source: Deploy from a branch
3. Branch: main → /root
4. Save

## 🏷️ 建議的 Repository 標籤 (Topics)

在 repository 首頁點選 "Add topics"，加入：
- `ai-education`
- `educational-technology`
- `concept-map`
- `cognitive-apprenticeship`
- `metacognition`
- `digital-literacy`
- `obsidian-canvas`
- `teaching-innovation`

## 📢 Repository 名稱建議

以下是幾個建議的 repository 名稱：

1. `ai-teaching-advantages-concept-map` ✅ 推薦
2. `ai-education-hierarchy-map`
3. `teaching-learning-ai-framework`
4. `digital-literacy-ai-concept-map`

## ✨ README 預覽提示

上傳後，GitHub 會自動渲染 README.md，確保：
- ✅ 所有標題正常顯示
- ✅ 列表格式正確
- ✅ 圖片連結有效（如果有的話）
- ✅ 表情符號正常顯示

## 🔗 完成後的連結格式

你的 repository 會在：
```
https://github.com/你的使用者名稱/ai-teaching-advantages-concept-map
```

## 💡 額外建議

### 建立 Issues 標籤
可以預先建立一些 issue 標籤方便後續管理：
- `enhancement` - 改進建議
- `question` - 問題討論
- `documentation` - 文件相關

### 建立 CONTRIBUTING.md（選填）
如果希望其他人貢獻，可以建立貢獻指南。

### 建立 CHANGELOG.md（選填）
記錄版本更新內容。

## ⚠️ 注意事項

1. **確認檔案大小**：GitHub 單一檔案限制 100MB
2. **檢查敏感資訊**：確保沒有個人敏感資訊
3. **選擇適當的授權**：MIT License 適合開放分享
4. **寫清楚 README**：讓其他人容易理解專案

---

完成上傳後，記得檢查 repository 是否正常顯示！

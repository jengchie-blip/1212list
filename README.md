<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# To-Do List & Workforce Monitor

A comprehensive workforce management dashboard featuring Timesheet Reporting, Statistics Monitoring, and Gemini AI assistance.

## ⚠️ 無法使用按鈕發佈？ (Cannot Publish?)

如果您點擊 "Publish to GitHub" 按鈕出現 **Something went wrong**，這是因為雲端環境的權限或專案設定衝突。

**請改用下方「終端機指令」手動發佈，保證成功：**

### 1. 建立 GitHub Repository
前往 [GitHub 新增 Repository](https://github.com/new)，輸入名稱（如 `todo-app`），建立後複製網址 (HTTPS)。

### 2. 在專案中執行指令
請在編輯器下方的 **Terminal (終端機)** 執行以下指令：

```bash
# 1. 初始化 Git
git init

# 2. 加入所有檔案
git add .

# 3. 提交變更
git commit -m "Initial commit"

# 4. 設定分支
git branch -M main

# 5. 連結 GitHub (請將網址換成您剛剛複製的網址)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# 6. 推送程式碼
git push -u origin main
```

推送成功後，GitHub Actions 會自動幫您部署網頁！

---

## Run Locally

1. Install dependencies:
   `npm install`
2. Run the app:
   `npm run dev`

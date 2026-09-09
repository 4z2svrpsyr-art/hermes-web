# Hermes Web 🚀

由 Hermes AI 自動產生的網頁專案。push code → 自動部署到 Vercel。

## 專案結構

```
hermes-web/
├── travel-plan/    # 旅遊規劃書（範例）
├── portfolio/      # 成果展示（範例）
└── README.md
```

每個子目錄是一個獨立網頁。

## 運作方式

1. Hermes 在子目錄內產生 HTML/CSS
2. `git add` → `git commit` → `git push`
3. Vercel 自動偵測 → 建置 → 部署
4. 回傳公開 URL

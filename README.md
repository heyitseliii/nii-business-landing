# 泥日教育 × 企業日文培訓 Landing Page

這是泥日教育 B2B 企業內訓的一頁式 Landing Page，供內部同事預覽、測試與提供修改意見。

## 線上版本

| 環境 | 網址 | 用途 |
|------|------|------|
| 正式站（Teachify） | [nii.school/business](https://nii.school/business) | 對外可分享，但目前 `noindex` 中 |
| 預覽站（GitHub Pages） | [niischool-tw.github.io/nii-business-landing/nii-business.html](https://niischool-tw.github.io/nii-business-landing/nii-business.html) | 此 repo 的最新 HTML 直接渲染 |

> ⚠️ 目前 HTML head 帶有 `<meta name="robots" content="noindex, nofollow">`，搜尋引擎與 AI 爬蟲不會索引此頁。
> 正式對外公開時，請把這行 meta 拿掉再重新 push（GH Pages 會自動更新）並重新部署 Teachify `/business`。
>
> Teachify 版本的圖片仍從 GitHub Pages 的 `images/` 載入，此 repo 是圖片資源來源，請勿任意刪除 `images/` 內檔案。

---

## 頁面結構

| # | 區塊 | 說明 |
|---|------|------|
| 1 | Hero | 主視覺、標語、CTA 按鈕 |
| 2 | 核心優勢 | 為什麼選擇泥日 |
| 3 | 三大主力課程 | 起步系列、職場日文術、1 對 1 |
| 4 | 合作流程 | 諮詢 → 規劃 → 開課 → 成效報告 |
| 5 | 聯絡表單 | 企業諮詢申請 |
| 6 | 內容授權 | 企業自有平台授權方案 |
| 7 | 客戶見證 | 合作企業回饋輪播 |

---

## 如何提供意見或回報問題

我們使用 GitHub Issues 來收集大家的修改建議與問題回報，不需要工程背景，幾個步驟就能完成。

### 開一個 Issue

1. 前往頁面上方的 [Issues](https://github.com/niischool-tw/nii-business-landing/issues) 分頁
2. 點選右上角的綠色按鈕「**New issue**」
3. 填寫標題與內容（說明在哪個區塊、看到什麼問題、希望如何調整）
4. 點「**Submit new issue**」送出

### Issue 寫法建議

**標題**：一句話說明問題，例如：
- `Hero 區 CTA 按鈕文字想改為「立即預約」`
- `手機版表單欄位排版跑掉`
- `客戶見證第二則內容需要更新`

**內容**：可以補充：
- 哪個區塊 / 哪個欄位
- 目前的狀況（可附截圖）
- 希望改成什麼樣子

### Issue 標籤說明

| 標籤 | 意思 |
|------|------|
| `bug` | 顯示錯誤或功能壞掉 |
| `enhancement` | 希望新增或優化的功能 |
| `content` | 文案、數字、資訊需要修改 |
| `question` | 有疑問想討論 |

---

## 本地預覽（可選）

如果想在本機打開頁面測試：

```bash
# 需要先安裝 Node.js
npx serve -p 3456 .
```

接著在瀏覽器開啟 `http://localhost:3456/nii-business.html`

---

## 檔案說明

```
nii-business.html   # 完整單頁 HTML（含 CSS 與 JS）
```

---

*泥日教育內部使用 · 更新於 2026-04-23*

# 簡報分享

網址：https://vm3vup54.github.io/slides/

每份簡報一個資料夾，資料夾裡放 `index.html`（單一離線 HTML 檔）：

```
slides/
├─ index.html          目錄頁（DECKS 清單）
├─ robots.txt          不讓搜尋引擎收錄
└─ YYYY-MM-主題/
     └─ index.html     → https://vm3vup54.github.io/slides/YYYY-MM-主題/
```

## 新增一份簡報

1. 建資料夾 `YYYY-MM-英文或拼音主題/`，把簡報複製成 `index.html`。
2. 在根目錄 `index.html` 的 `DECKS` 最上面加一筆 `{date, path, title, summary}`。
3. 指定檔案 `git add` → `git commit` → `git push`，約 1 分鐘後網址生效。

## 注意

- 這是**公開網站**，只放可以公開的簡報；內部簽辦、未定案或含個資的內容不要放。
- 已設定 `noindex` 與 `robots.txt`，降低被搜尋引擎收錄，但知道網址的人都看得到。

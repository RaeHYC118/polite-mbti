# 禮貌版 MBTI

一個 24 題五點量表的小測驗,測出你的四字母「禮貌型」。單一 `index.html`,無任何外部相依,直接用瀏覽器打開就能玩。

## 放到 GitHub Pages(最簡單的方式)

1. 在 GitHub 建立一個新的儲存庫(Repository),例如取名 `polite-mbti`,設為 **Public**。
2. 把 `index.html` 上傳進去(可以直接把檔案拖進網頁,或用 git push)。放在儲存庫的根目錄。
3. 進入該儲存庫的 **Settings → Pages**。
4. 在「Build and deployment」的 **Source** 選 **Deploy from a branch**;Branch 選 `main`、資料夾選 `/ (root)`,按 **Save**。
5. 等約 1 分鐘,頁面上方會出現網址,格式是:
   `https://你的帳號.github.io/polite-mbti/`
   打開就是你的測驗網站,這個連結可以直接分享給朋友。

## 想用網址列出更漂亮的名稱?

- 把儲存庫命名為 `你的帳號.github.io`,網站網址就會是 `https://你的帳號.github.io/`(不帶子路徑)。

## 之後想修改

- 直接編輯 `index.html` 再存回儲存庫即可,GitHub Pages 會自動重新部署。
- 題目在檔案裡的 `Q` 陣列、16 型說明在 `T` 物件,想改文案或加題都在那裡。

## 用本機預覽

不想上傳也可以先在自己電腦看:直接雙擊 `index.html` 用瀏覽器開啟即可。

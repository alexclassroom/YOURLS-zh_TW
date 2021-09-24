# YOURLS-zh_TW：YOURLS 1.8.2 縮址服務台灣漢文語言套件

開源專案的語言套件完成之後，少有定時、持續維護的案例。YOURLS 找的到的舊版台灣漢文語言套件，已有多年沒有維護，加上缺漏新版本 YOURLS 的新增字串譯文，因此阿力獅依據台灣標準資訊用語及資訊本地化業界的台灣中文譯文樣式規範，重譯一份最新版譯文。YOURLS 會與我本地化的其他 WordPress 外掛/佈景主題台灣中文語言套件一樣，持續維護下去。

請注意，這是全新翻譯版本，若有任何疑問、譯文錯誤或需要修改的地方，請與我聯絡，例如在 [Issues] 分頁提出問題。

# YOURLS 官方本地化詳細資料：

請參考 [https://github.com/YOURLS/YOURLS/wiki/YOURLS-in-your-language](https://github.com/YOURLS/YOURLS/wiki/YOURLS-in-your-language)。
## 安裝方式

1. 下載 `zh_TW.mo` 檔案。如有需要自行修改譯文的需求，才需要下載 `zh_TW.po` (譯文檔案) 及 `YOURLS.pot` (譯文範本檔案)。
2. 開啟自建 YOURLS 服務網站 `user` 目錄中的 `config.php`，然後編輯或新增以下常式：
    - `define( 'YOURLS_LANG', 'zh_TW' );`
3. 將 `zh_TW.mo` 檔案上傳至 `user/languages` 目錄。

## 使用授權

使用與 YOURLS 專案相同的 MIT 授權。

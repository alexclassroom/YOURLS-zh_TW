# YOURLS 1.10.2 縮址服務台灣漢文語言套件
開源專案的語言套件完成之後，少有定時、持續維護的案例。之前找的到的 [YOURLS](https://github.com/YOURLS/YOURLS) 舊版台灣漢文語言套件，已有多年沒有維護，加上缺漏新版本 YOURLS 的新增字串譯文，因此阿力獅依據台灣標準資訊用語及資訊本地化業界的[台灣漢文譯文樣式規範](https://tw.wordpress.org/team/handbook/handbook/zh-tw-localization-style-guide/)，**全新重譯**一份最新版譯文。YOURLS 會與阿力獅本地化的其他 WordPress 外掛/佈景主題台灣中文語言套件一樣，持續維護下去。

請注意，這是全新翻譯版本，若有任何疑問、譯文錯誤或需要修改的地方，請在這個存放庫的 [[Discussions](https://github.com/alexclassroom/YOURLS-zh_TW/discussions)] 分頁以**新增討論串**方式提出。

# 贊助阿力獅的全職社群資訊本地化工作
1. 🎁 贊助阿力獅的全職本地化工作：[藍新金流](https://suo.fyi/donate-alexlion-blue)
2. 🧧 海外人士贊助阿力獅的全職本地化工作：[台灣 PayPal 帳號](https://suo.fyi/donate-alexlion-paypal)，僅限**台灣以外**國家/地區 PayPal 帳號可以贊助
3. 🎖️ 懇請**每年贊助新台幣 1200 元/美金 40 元等值或倍數金額**
4. 🎗️ **每年 365 人/份贊助**，讓阿力獅的全職社群本地化工作走的更遠更久
5. 歡迎加入 Facebook 公開社團《[你我他的 WordPress 使用心得及阿力獅的台灣漢文本地化](https://www.facebook.com/groups/wordpresstwhant)》

# YOURLS 官方本地化詳細資料：
- 請參考這份[官方線上說明](https://yourls.org/docs/guide/extend/languages.html)。
- 如需取得 YOURLS 開發者目前提供的其他語言套件，請點擊這個[連結](https://github.com/YOURLS/awesome#translations)。請注意，阿力獅全新重譯本地化的台灣漢文語言套件 GitHub 存放庫 (就是你現在看到的這一個)，名列 YOURLS 官方 GitHub 存放庫中。

## 譯文樣式參考依據
請參考〈[台灣正體中文資訊本地化譯文樣式指南](https://tw.wordpress.org/team/handbook/handbook/zh-tw-localization-style-guide/)〉。

## 安裝方式
1. 下載 `zh_TW.mo` 檔案。如有自行修改譯文的需求，才需要下載 `zh_TW.po` (譯文檔案) 及 `YOURLS.pot` (譯文範本檔案)。
2. 開啟自建 YOURLS 服務網站 `user` 目錄中的 `config.php`，然後編輯或新增以下常式：
    - `define( 'YOURLS_LANG', 'zh_TW' );`
3. 將 `zh_TW.mo` 檔案上傳至 `user/languages` 目錄。

## 使用授權
使用與 YOURLS 專案相同的 [MIT 授權](https://opensource.org/licenses/MIT)。

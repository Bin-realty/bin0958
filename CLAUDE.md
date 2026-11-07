# 蘇聖斌 個人品牌站（公開 repo）

網址：https://bin-realty.github.io/bin0958/

- 純靜態、單檔 HTML、無 build。**上線方式：Pages 目前吃 `gh-pages` 分支**（GitHub 自動啟用的），所以每次改完要 `git push origin main` 再 `git push origin main:gh-pages`，兩個都推才會更新。（聖斌若哪天在 Settings → Pages 把來源改成 main，就不用再推 gh-pages。）
- 頁面：index.html 品牌首頁｜listing.html?code=L001 物件頁｜mortgage.html 房貸試算｜needs.html 找房需求單｜sites.html 網站總覽。
- 物件資料從 threads-poster 的 data/listings.json 直接讀（raw.githubusercontent），照片讀 threads-poster listings/<code小寫>/album/NN.jpg；本 repo 不存物件資料。
- 公開 repo：絕不放客戶、屋主、電話、門牌號、底價、內部紀錄。聯絡資料只放名片上的公開資訊。
- 稱呼一律「聖斌／蘇聖斌」。文案規則與署名見 threads-poster/CLAUDE.md；私人規則在 realty-data（私人 repo）。
- 風格：深藍綠 #0f4c5c ＋ 台灣房屋橘 #e8731a，與 mortgage.html 同一套；手機 390px 不可橫向捲動。

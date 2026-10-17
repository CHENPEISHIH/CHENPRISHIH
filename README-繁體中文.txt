陳佩詩免費靜態作品集網站

檔案內容
- index.html：首頁
- jin-gong.html：作品《僅供使用》的內頁
- style.css：版面樣式
- images：你提供的兩張照片

如何免費上線（建議用 iPad Safari）
1. 登入 GitHub，建立一個新的公開 repository，名稱可用 chen-pei-shih.github.io（若這個名稱可用）。
2. 將這個 ZIP 解壓縮，進入資料夾，把 index.html、jin-gong.html、style.css 和 images 資料夾裡的檔案上傳到 repository 根目錄（images 資料夾需保留）。
3. 在 repository 的 Settings → Pages，將 Build and deployment 設為 Deploy from a branch，選 main 和 /(root)，按 Save。
4. 等待部署完成，GitHub Pages 會提供網站網址。官方說明：https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
5. 若 repository 名稱是 chen-pei-shih.github.io，網址通常是 https://chen-pei-shih.github.io/；若使用其他名稱，網址會包含 repository 名稱。以 GitHub Pages 顯示的網址為準。

新增《僅供使用》的其他照片
1. 在 images 資料夾上傳新照片，例如 jin-gong-02.jpg。
2. 用 GitHub 編輯 jin-gong.html，在 gallery 區塊新增一行：
   <img src="images/jin-gong-02.jpg" alt="《僅供使用》作品細節">
3. 儲存變更，等待網站更新。

新增作品
1. 新增一個作品頁 HTML（可以複製 jin-gong.html 再修改）。
2. 把作品照片上傳到 images。
3. 在 index.html 的 works 區塊，複製 article.work 區塊，修改連結、圖片、作品名稱、年份和媒材。
4. 儲存變更。

注意
- GitHub Pages 免費方案的網站是公開的，請不要上傳私人或敏感資料。
- 這是靜態網站，新增作品需要編輯 HTML；不像 WordPress 有方便的作品管理後台。
- 免費提供 github.io 網址；自己的網域通常需要另外購買。

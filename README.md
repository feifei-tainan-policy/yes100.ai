# yes100.ai

https://yes100.ai/island/ 是 https://feifei-tainan-policy.com/island/（最新版台南政策島）的同步複本。

- `island/`、`posters/` 和根目錄的 favicon 由 [feifei-tainan-policy.github.io](https://github.com/feifei-tainan-policy/feifei-tainan-policy.github.io) 的 GitHub Actions「Sync island to yes100.ai」產生：官網每次部署成功就自動同步。**不要直接改這些檔案**，請改官網 repo 的 `public/island/`。
- 網址的換法寫在官網 repo 的 `scripts/island-mirror.mjs`：分享用的網址換成 yes100.ai，canonical 保留原站，「回到 6 大政策影片」連回原站首頁。
- `index.html`（首頁直接轉到 /island/）、`404.html`、`CNAME` 在這個 repo 裡改。
- 手動重新同步：官網 repo → Actions → Sync island to yes100.ai → Run workflow。

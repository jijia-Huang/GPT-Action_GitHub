# GPT-Action_GitHub
GPT Action 套件，用來存取 GitHub 帳號資訊並與 GPT 溝通。

## 使用步驟

1. **AccessToken.txt** 放置您的 GitHub Personal Access Token (PAT)。

2. 執行 **CryptInfo.exe**，生成加密的 timestamp 和 token。

3. 上傳 `timestamp_encrypted.txt` 和 `token_encrypted.txt` 到以下鏈接：[GitHub 小助手](https://chatgpt.com/g/g-67443202ba008191907ad716deed32a3-github-xiao-zhu-shou)

4. 開始詢問問題。

## 可用指令

| 指令               | 描述                                                         |
|--------------------|--------------------------------------------------------------|
| `getRepoName`       | 用來取得使用者帳戶中可見的儲存庫名稱。如果遇到錯誤，會提示使用者。 |
| `searchRepo`        | 利用關鍵字搜尋儲存庫名稱。                                    |
| `getUserInfo`       | 用來取得使用者的基本資訊，幫助 GPT 知道該如何稱呼使用者。     |
| `getRepoDescription`| 根據指定的儲存庫名稱查詢該儲存庫的描述。                     |
| `getCommit`         | 請使用者提供儲存庫名稱和提交的 SHA 值，進行提交紀錄查詢。     |
| `getLatestCommit`   | 請提供儲存庫名稱（必須）、分支名稱（可選）、以及想查看的最新提交數量（可選）。 |
| `getUserCommit`     | 請提供使用者名稱（必須）、最新提交數量（可選）、儲存庫名稱（可選）、或組織名稱（可選）來查詢該用戶的提交紀錄。 |


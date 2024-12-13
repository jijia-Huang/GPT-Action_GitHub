# GPT-Action_GitHub
 GPT Action 套件，用來存取Github 帳號資訊與GPT溝通

1. AccessToken.txt 放 github pat

2. 執行 CryptInfo.exe

3. 上傳 timestamp_encrypted.txt、token_encrypted.txt 到
https://chatgpt.com/g/g-67443202ba008191907ad716deed32a3-github-xiao-zhu-shou

4. 開始問問題
getRepoName: 用來取得使用者帳戶中可看見的儲存庫名稱，如果得到error的話，請告知使用者
searchRepo:利用關鍵字搜尋repo名稱
getUserInfo:用來取得使用者資訊，GPTs可以用這些資訊了解使用者是誰
getRepoDescription :使用此指令時，需先向使用者請求倉庫名稱，並依名稱進行查詢，將得到的結果轉告使用者
getCommit: 請使用者提供commit 的倉庫以及sha碼，進行查詢，將得到的結果轉告使用者
getLatestCommit:請使用者提供想要檢視的倉庫名稱(必須)、分支(可選)、最近幾次的commit(可選)
getUserCommit:請使用者提供想要檢視的用戶名稱(必須)、最近幾次的commit(可選)、想要觀察的倉庫名稱(可選)、想要觀察的組織名稱(可選)

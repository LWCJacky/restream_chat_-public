# restream_chat教學
* [restream](https://app.restream.io/)是一個提供跨平台同步串流的服務
* restream_chat是用來擷取由restream平台提供的聊天室api轉送到discord
* 目前可以轉發FB和YOUTUBE的聊天至DISCORD
* 使用前提:
    * 在DISCORD伺服器中必須要有webhooks權限
    ![](https://i.imgur.com/69o7KRC.png)
    * 你必須透過[restream](https://app.restream.io/)進行直播
## 開始使用
https://lwcjacky.github.io/restream_chat_public/
點擊上方連結進入網站


---
* 你會看到第一個畫面
![](https://i.imgur.com/dE0XW8z.png)
* 點擊開始連動，網頁會進行跳轉
![](https://i.imgur.com/BycgnmH.png)
* 上方顯示的restream官方提供的登入畫面輸入的帳密不會傳到restream_chat的伺服器，請放心服用!
* 登入後依照指示點擊授權，授權成功網頁會自動跳轉回restream_chat進行授權認證
* 認證成功後會顯示輸入webhooks網址的輸入框
![](https://i.imgur.com/7bzLRT2.png)
### 取得Discoed-webhooks網址
* **只要有webhooks權限就可以在頻道中看到設定**
![](https://i.imgur.com/H3rJWJ0.png)
點擊設定
* 進入整合頁面 
![](https://i.imgur.com/6D5Y96F.png)
* 你可以創建新的webhooks或選擇舊有的webhooks
![](https://i.imgur.com/XN8fpYx.png)
* 按下複製webhooks連結
* **恭喜你成功取得webhooks連結**

### 最後一步
* 將連接貼到輸入欄位
![](https://i.imgur.com/FHEWUKV.png)
* 點擊連接
* 輸入錯誤或連接失敗右下方會有錯誤提示
![](https://i.imgur.com/GDUw8by.png)
* 成功連接後會自動跳轉回主畫面，並在左下角提示連接成功
![](https://i.imgur.com/6Diqp4Z.png)
* **開始享受吧~~~**

## 注意事項 
* 單次授權時間為2個小時，授權將會失效。
* 請勿短時間內多次同帳號連動，目前系統還只是公開預覽版，部分防呆機制待完成。
* 帳號連動後無法手動取消，需等待授權過期
> [name=李捷Jacky]







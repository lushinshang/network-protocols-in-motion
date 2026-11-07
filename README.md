# 網路協定，動起來 · Network Protocols, in Motion

> 封包怎麼走　協定怎麼說 · How Packets Travel, How Protocols Talk

14 個網路協定、78 個步驟、每步附旁白、可拖曳時間軸的互動教學動畫，中英並列。看得見封包怎麼走，比背 OSI 七層更想學下去。

👉 **線上看：https://lushinshang.github.io/network-protocols-in-motion/**

## 兩種看法

| | 風格 | 怎麼看 |
|---|---|---|
| **A 封包旅程** · The Packet's Journey | 暗色 | 跟著一個封包，從你的電腦出發到伺服器再回來 |
| **B 分層剖面** · Stack Anatomy | 淺色 | 把封包一層層拆開，看每一層貼了什麼標頭 |

入口頁單屏、不捲動：桌面橫向、手機直向。

## 涵蓋的協定

HTTP、HTTPS、TCP、UDP、IP、DNS、DHCP、ICMP、SMTP、POP3、IMAP、FTP、SSH、TLS。

直接開某個協定（把 `tcp` 換成上面任一個小寫 id）：

- `a-journey.html?p=tcp`
- `b-section.html?p=tcp`

## 操作

- 鍵盤：`←` `→` 換步驟、`Space` 或 `K` 播放／暫停、`[` `]` 調速、`M` 開關旁白、`Home` `End` 頭尾
- 時間軸可拖曳；手機可滑動換站
- 旁白為預錄的 AI 合成語音

## 檔案

三個獨立 HTML 檔，離線可用，沒有外部相依：

- `index.html` — 入口頁
- `a-journey.html`、`b-section.html` — 兩種動畫（各約 8.7 MB，旁白內嵌）

## 已知限制

- 以無頭 Chrome 與模擬手機驗證；真機、Safari／Firefox、螢幕閱讀器未驗證
- 動畫畫面本身為中文介面，英文只出現在標題、入口頁與部分標示

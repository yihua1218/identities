# Nuxt.js

前端介面使用 Nuxt.js + Bootstrap。

## 需求

1. 可以隨時切換使用不同的後端環境，例如從本地端的 golang REST API 切換至遠端的 API Server。
2. 只有在使用本地端環境時，能夠修改變本地端的環境變數，例如變更和設定 Facebook App ID 等等。
3. 需要支援多語系，多語系的支援，需要能隨時切換語系。每個區域語系，都能有各自的版本控制，可在不同版本的語系檔即時切換。
4. API 可切換使用 Websockt 或 REST API，以 Webwocket 為優先，若無法成功建立 Webwocket 再退回使用 REST API。 
5. 其他想到再補充。

## Websocket Hosting

不論使用何種方式實作 Websocket，都希望能夠隨時切換使用。並且要想好一個安全的身分識別驗證機制。

1. 用 AWS IoT 來串接使用 API Gateway 或 Lambda。
2. Azure 的 Web Sites 支援 WebSockets，可以研究一下怎麼使用。
3. [Fanout](https://fanout.io/) 的 Free Plan，但只有 500 messages / day 的免費使用量。
4. Golang 實作 Websocket to API Gateway 或 Lambda 的 Proxy，在 EC2 上執行。應該已經有 Open Source Project，需要找一找。
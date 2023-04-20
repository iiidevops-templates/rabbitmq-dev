## 部署開發用 RabbitMQ
- :warning: 此部署僅為測試環境開發階段使用，為單節點配置，如需部署至 Production 環境，請另外修改配置設定, 不要直接使用
- :information_source: 這部署並無配置永久資料儲存功能(符合開發情境提供快速還原乾淨環境的作法)，只要專案 repo 有commit更動就會進行資料重置，請commit/push前要謹慎注意。

## 使用說明

### 啟動自動匯入資料的方式

1. 目前 [RabbitMQ](https://hub.docker.com/_/rabbitmq) 使用 3 的版本，可依需求進行調整。
2. 可修改 iiidevops/app.env 內的設定內容來修改預設帳號與密碼。
3. 建置完成後，請從「實證環境」中獲取的服務連線資訊進入使用。


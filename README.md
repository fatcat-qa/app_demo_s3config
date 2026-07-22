# app_demo_s3config

## 修改App開啟的URL
編輯s3config_demo.json裡面的appUrl欄位，改成想要的網址後commit change後，會自動進行部署到github pages

在code分頁可以看到部署狀態，褐色圈圈代表是部署中
<img width="790" height="421" alt="image" src="https://github.com/user-attachments/assets/6266a5d2-9834-4ffe-8232-3273d000b29c" />
綠色勾勾代表部署完成
<img width="817" height="399" alt="image" src="https://github.com/user-attachments/assets/a2e51291-d5f7-4ad1-a156-79e268504d3c" />

可以透過以下網址確認變更狀態
[https://fatcat-qa.github.io/app_demo_s3config/s3config_demo.json](https://fatcat-qa.github.io/app_demo_s3config/s3config_demo.json)


## 開啟特殊debug介面
s3config_demo.json裡面的feature.debugPanel欄位為true時，用手機開啟以下網址後點擊解鎖JVDDEMO後在app裡面會有deubg介面，可以看到從app內送出的通訊記錄

[https://fatcat-qa.github.io/app_demo_s3config/debug-unlock.html](https://fatcat-qa.github.io/app_demo_s3config/debug-unlock.html)

<img width="704" height="735" alt="image" src="https://github.com/user-attachments/assets/25ca7de8-69b0-4edb-b295-5755132e5c20" />


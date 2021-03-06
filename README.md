# Identities

身分識別，為什麼需要進行身分識別？為了提供客製化的自訂服務，提供差別資訊和各種個人訂閱服務。

一個不需要使用者帳號和密碼來識別身分的系統，能透過什麼方式識別身分？為什麼不要用帳號和密碼來識別身分？

## 可用的識別資訊

可以用來作為身分識別的資訊來源，需要是可以被驗證的。

1. E-mail
2. 在瀏覽器用戶端產生的 UUID
3. 應用程式所產生的 UUID
4. 第三方登入
5. 電話號碼

## 避免使用的識別資訊

不該被用來作為身分識別的資料來源，無法被驗證，或者是涉及隱私的敏感性資訊。

1. 身分證字號
2. 護照號碼
3. 出生日
4. 性別
5. 姓名

## 安全的身分回復方式和流程

1. 透過 E-mail 回復
2. 透過電話回復
3. 自訂問題

## 自然人身分與非自然人身分

自然人身分，做為系統上不可重複的識別身分，可多種識別資訊來源連結。非自然人身分，則是需要由被授權的自然人身分在取得授權後，切換為非自然人身分。

## 身分連結

自然人與非自然人，皆可以與多種識別資訊產生連結和中斷連結。

## 應用程式授權

將身分識別授權給應用程式，提供各種應用程式，儲存該應用程式的客製化訂閱資訊。每個應用程式，可能會有多個用戶終端操作方式存取使用，從瀏覽器、手機應用程式，或者是桌面應用程式，都是不同的用戶終端。

## 依序支援的第三方登入

1. Google
2. Facebook
3. Twitter
4. GitHub
5. LINE
6. WeChat

## 基本政策

1. 不儲存敏感性個人資訊
2. 不儲存密碼
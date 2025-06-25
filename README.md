# Postman API 測試練習 — DummyJSON CRUD 測試
使用 Postman 工具測試公開 API 的實作練習，透過 DummyJSON API 進行完整的 CRUD 操作，<br>
並搭配測試腳本驗證回傳資料與狀態碼，模擬實際 API 測試流程<br>
### 測試項目:<br>
#### 1.GET 所有商品<br>
-測試是否成功取得商品列表（狀態碼為 200）<br>
-驗證回傳資料中是否包含 `products` 陣列 <br>
#### 2.POST 新增商品<br>
-使用 JSON Body 新增一筆測試商品（`title: MyTestProduct`）<br>
-驗證回傳資料中 `title` 是否正確<br>
#### 3.PUT 修改商品<br>
-修改指定商品 ID 的名稱為 `UpdatedTitle`<br>
-驗證回傳資料的 `title` 欄位已變更<br>
#### 4.DELETE 刪除商品<br>
-發送刪除請求，驗證是否成功（狀態碼 200）<br>

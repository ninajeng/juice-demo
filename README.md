## Juice oasis 線上點餐系統

實體門市搭配線上點餐系統，為用戶提供便捷、多元的訂餐體驗。除了瀏覽菜單資訊、訂購餐點外，還提供了加入收藏、設定常用訂購資料等功能，讓用戶能快速又便利地完成訂單。

<br>

## 使用技術
- [Vue.js](https://vuejs.org/) <small>Vue3 with Options API</small>
- [Vite](https://vitejs.dev/) <small>環境</small>
- [Node.js](https://nodejs.org/en) <small>環境</small>
- [Bootstrap5](https://getbootstrap.com/) <small>CSS Framework</small> 
- [Pinia](https://pinia.vuejs.org/) <small>狀態管理</small>
- [Git](https://git-scm.com/) <small>版本管理</small>
- [GitHub](https://github.com/) <small>專案部屬</small> 
- [Render Server](https://render.com/) <small>模擬伺服器</small> 
- [Vue Router](https://router.vuejs.org/) <small>路由管理</small> 
- [Axios](https://github.com/axios/axios) <small>發送 HTTP 請求</small> 
- [VeeValidate](https://vee-validate.logaretm.com/v4/) <small>表單驗證</small>
- [json-server](https://www.npmjs.com/package/json-server) <small>用戶帳號註冊、登入</small>  
- [Swiper](https://swiperjs.com/) <small>輪播效果</small>  
- [SweetAlert2](https://sweetalert2.github.io/) <small>彈跳視窗</small> 
- [vue-loading-overlay](https://www.npmjs.com/package/vue-loading-overlay) <small>loading 效果</small>

<br>

## 功能簡述

**前台**

**首頁**
- 用戶可以瀏覽店家特色
- 用戶可以瀏覽店家欲推廣的水果知識，並連結相關產品
- 用戶可以瀏覽店家的活動優惠
- 用戶可以瀏覽其他客戶的評論
- 用戶可以瀏覽會員功能資訊

<br>

**導覽列**

- 用戶可以連結至各頁面
- 用戶可以登入或登出系統

<br>

**菜單頁**

- 用戶可以依序瀏覽菜單品項，或是使用分類、查詢功能，搜尋相關品項
- 用戶可以瀏覽產品成分與產品描述資訊
- 用戶可以指定飲品的喜好甜度、冷熱、尺寸，並將該品項加入購物車
- 用戶可以將產品加入收藏
- 用戶可以點擊按鈕來複製頁面連結
- 用戶可以點選連結到單一產品頁，瀏覽其他資訊

<br>

**單一產品頁**

- 著重於呈現產品資訊與注意事項，並且讓用戶能收藏產品、分享產品連結，以及將產品加入購物車
- 用戶可以瀏覽產品成分與產品描述資訊
- 用戶可以瀏覽產品注意事項
- 用戶可以指定飲品的喜好甜度、冷熱、尺寸，並將該品項加入購物車
- 用戶可以將產品加入收藏
- 用戶可以點擊按鈕來複製頁面連結

<br>

**登入 / 註冊頁**

- 用戶可以填寫資料並註冊成為會員
- 用戶可以使用登入會員功能

<br>

**個人資料頁**

- 用戶可以修改會員基本資料
- 用戶可以變更密碼
- 用戶可以設定常用訂購人資料

<br>

**我的收藏頁**

- 用戶可以瀏覽、修改或刪除已收藏的產品品項
- 用戶可以將已收藏的產品加入購物車

<br>

**訂單紀錄頁**

- 用戶可以瀏覽訂單狀態與相關訂單資料

<br>

**購物車結帳頁 - 1.確認訂單**

- 用戶可以瀏覽、修改或刪除購物車內的品項
- 用戶可以修改購物車內品項的數項
- 用戶可以瀏覽產品成分與產品描述資訊
- 用戶可以將產品加入收藏
- 用戶可以點擊按鈕來複製頁面連結
- 用戶可以查閱或清除瀏覽紀錄
- 用戶可以瀏覽訂單明細，並套用優惠碼

<br>

**購物車結帳頁 - 2.填寫資料**

- 用戶可以填寫訂購人資料，或點擊按鈕將會員設定資料自動填入訂購表單
- 用戶可以送出訂單或選擇回到上一步
- 用戶可以瀏覽訂單明細

<br>

**購物車結帳頁 - 3.完成訂單**

- 用戶可以瀏覽訂單狀態與訂單相關資訊
- 用戶可以點選按鈕連結至菜單頁面

<br>

**後台**

**登入頁**

- 管理者可以登入後台系統

<br>

**產品管理**

- 管理者可以瀏覽產品列表、單一產品資訊
- 管理者可以新增或刪除產品
- 管理者可以編輯產品資料、設定產品的客製化選項等功能

<br>

**優惠券管理**

- 管理者可以瀏覽優惠券列表、單一優惠券資訊
- 管理者可以新增或刪除優惠券
- 管理者可以編輯優惠券資料內容、設定啟用或停用等功能

<br>

**訂單管理**

- 管理者可以瀏覽訂單列表、單一訂單資訊
- 管理者可以修改訂單狀態或刪除訂單

<br>

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
<br>

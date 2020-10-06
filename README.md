# tp_cooc_config


台北親師生拉出模組的暫時解法

* features web app 列表
* devMode 開發模式
* userMode 釋出模式

組合順序為 school-specific 先行後接 basic-config, 若需要完全自定義順序, 全部都寫至 school-specific 即可

            "headerHide": 是否顯示 header (有返回)
            "imgURI": 圖片位址
            "label": app 上顯示名稱
            "featureURI": web app 網址
            "production": 是否上架
            "nickname": 註解或是暱稱
            "urlProcessed": 是否帶參數 (token, uuid...)
            "openOnBrowser": 另開瀏覽器嗎
            "isWebApp": 是不是 web app
            
            如果不是 webApp 會多讀以下三個參數, 用 tronclass 舉例
            "deepLink": "tronclass://open.it",
            "appleStore": "https://apps.apple.com/tw/app/tronclass-%E6%9A%A2%E8%AA%B2/id973028199",
            "googlePlay": "https://play.google.com/store/apps/details?id=com.wisdomgarden.trpc",


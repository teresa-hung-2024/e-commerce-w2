Discord 使用者名稱: Hayaka

作業網址：請提供 GitHub Pages 以及 Github Repo 連結，以方便助教與講師檢視（可以參考課程影音「Github Pages 免費架站空間教學」上傳方式）


訓練菜單：
2.2 幾乎全程使用 emmet 來開發
2.3 網頁排版縮排

另外作業再參考助教直播後有幾個問題想問：



1.為什麼用 padding-left 而不是 margin？

在這段程式碼中：

<p class="h5 text-primary-400 mb-16">NT$2,600<del class="del-price">NT$3,200</del></p>

為什麼 NT$2,600 和 NT$3,200 這兩個元素之間的距離是使用 padding-left 來控制，而不是用 margin-left 或 margin-right？兩個元素之間的距離不是通常用 margin 來處理嗎？



2.為什麼不用通用間距 class？

承接問題一，既然 del-price 這個 class 裡面設定了 padding-left，為什麼不直接在class中下共用的間距像是 pl-8，而是要在專門的 CSS class 裡面設定？這樣做是因為這個間距在整個網站中只會使用這麼一次嗎？



3.間距設定的位置規則是什麼？

承接前兩個問題，我發現有時候間距會寫在特定的 class 內部（像是 .del-price { padding-left: 8px; }

），有時候又會直接在 HTML 的 class 屬性中使用共用間距 像是 class="pl-8" 或 class="mb-16"。想請問這兩種做法是基於什麼考量來決定的？什麼情況下應該把間距寫在專用 class 裡面，什麼情況下應該使用共用的間距？



4.想問為何 h4 標籤可能套用的是 h6 樣式，而不是一開始就先對好，自訂 .h4 就是用 h4 標籤的統一樣式之類


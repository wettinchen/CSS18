## Chapter 18: Card Project
It is my coding practice with the TUTORIAL of Dave Gray. 

## Source
### Dave Gray 的 CSS 資源
https://github.com/gitdagray/css_course

### Dave Gray 的 CSS 課程
https://youtube.com/playlist?list=PL0Zuz27SZ-6Mx9fd9elt80G1bPcySmWit

### Dave Gray 的 YouTube 頻道
https://www.youtube.com/@DaveGrayTeachesCode

## Quick Concept outline
###  1. Intro
        教學影片固定的開頭

###  2. Welcome
        歡迎觀眾，說明工具與資料位置

###  3. Project Preview
        專案預覽

###  4. Starter Code
        初始設定說明

###  5. HTML structure
        修改 html

###  6. CSS Styles
        修改 CSS

###  7. CSS Reset
        進行 CSS 圖片的重設。
        在 img 設定 display 為 block，最大寬度為 100%，高度為 auto。

###  8. Utility Classes
        設定 nowrap 使名字不因換行分隔。
        將 Jane 的職稱 Dev Rel 設定 span元素 class 為 nowrap，
        white-space 為 nowrap

###  9. General Styles
        修改 CSS
        (1)刪除 header, nav, main, footer的樣式設定。在 header, footer 設定文字置中
        (2)刪除 nav 文字設定為黑色。
        設定 font-weight 為 bolder，display 為 flex，justify-content 為 space-evenly
        (3)設定已訪視連結的文字為黑色。
        (4)設定懸停和用 tab 選取的文字為黑色，亮度為 20%，透明度為 60%。
        (5)在 main 中，設定 dispaly 為 flex，flex-direction 為 column，
        align-items 為 center，gap 為 1.5rem，padding 為 1rem

### 10. card class styles
        (1)在 .card 中，設定 scroll-margin-top 為 8rem
        (2)設定寬度為 100% 或 350px 的最小值
        (3)設定背景為 #cbd5e1
        (4)設定 border 為 2px solid #000，border-radius 為 15px
        (5)設定 padding 為 1rem
        (6)設定 display 為 flex，flex-direction 為 column，align-items 為 center，發現名字和職稱沒有置中
        (7)在 .card figure 設定 display 為 flex，flex-flow 為 column nowrap ，使名字和職稱置中
        (8)在 .card img 設定 border 為 5px double #333，border-radius 為 50%
        (9)在 .card figcaption 設定 font-weight 為 bolder，字體大小為2rem，margin 為 1rem，文字置中
        (10)在 html 設定 scroll-behavior 為 smooth，使網頁滑動變得平緩。

### 11. Small breakpoint media query
        刪除原本的 Small media query 內容。
        設定 main 中，justify-content 為 center，flex-flow 為 row wrap，padding 為 1rem。
        設定 .card 寬度為 100% 或 400px 的最小值。
        設定 .card 的最後一個元素 Jane 會排列到最上面。

### 12. Medium breakpoint media query
        刪除原本的 Medium media query 內容。
        設定 nav 中，display 為 none。
        設定 .card 寬度為 100% 或 325px 的最小值。
        設定 .card figure 中，flex-flow 為 column-reverse
        設定 .card figcaption 中，margin 為 0.1em 0
        設定 .card p 中，margin-top 為 1rem

### 13. Large and XL breakpoints
        (1)刪除原本的 Large media query 內容。
        設定 .card 寬度為 100% 或 400px 的最小值。設定 .card 第二個元素的 order 為 -1
        (2)刪除原本的 XL media query 內容。
        設定 .card 寬度為 33% - 1rem 或 500px 的最小值。

### 14. Testing the breakpoints
        測試 Small, Medium, Large, XL breakpoints

### 15. Mobile device landscape breakpoint
        刪除原本的 Mobile device landscape media query。
        設定 h1 的 font-size 為 1.5rem，
        設定 nav 的 display 為 none，
        設定 main 的 flex-flow 為 row nowrap，justify-content 為 space-evenly，align-items 為 stretch。
        設定 .card 寬度為 33% - 0.25rem 或 200px 的最小值。
        設定 .card figcaption, .card p 的文字大小為 1.25rem。

### 16. Experiment and make it your own
        在 Medium media query 內容，移除 .card figcaption 中，margin 為 0.1em 0

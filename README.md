「正風毛筆字體」是基於[衡山毛筆フォント行書](https://opentype.jp/kouzangyousho.htm)的開放原始碼中文字型。衡山毛筆行書字體是來自於日本書法家青柳衡山，修改前文字＋符號數：7,582字，修改後文字＋符號數：23,699字。

## 字體特色

### 彌補繁體中文常用字缺字缺憾

第一階段的補字已補齊台灣教育部列出的 4,808 個常用字全都都補齊了，還是有些日常生活的常用字沒有補到。下圖是莫大毛筆（第一行）和正風毛筆（第二行）的比較：

![正風毛筆字體](https://github.com/max32002/masafont/raw/master/preview/preview.png)

相較於正風的師兄（莫大），正風個性上就隨性很多，也造成有部份的一些字很粗，而有些字極細。原作者的「木」、「米」、「禾」系列常常會少一撇，是正常的，第一次看到會覺得有點怪，看久就會習慣了。

目前完整新增字略長，中文字的部份新增11,467字，字數太多，請參考文字檔 [added_glyph.txt](https://github.com/max32002/masafont/raw/master/added_glyph.txt)。

附註： 由於是「非原作者」的補字，新加入的字在風格上，雖然盡力求一致，難免會與原作者會有一些不同。有很多很多字補的「超級醜」的，幾乎大部份的字都有改善空間，如果有好心人有重做那些醜到爆（或長像怪怪）的字，請再寄給我，感謝。

原版的正風毛筆的中文字比補他師兄（莫大毛筆）的字少很多，家徒四壁，家裡連「桌」字都沒有。

科普「JIS第二水準漢字」：是日本工業規格協會制訂的編碼對應表，收錄6879個圖形字符，包括6355漢字和524個非漢字圖形符號。JIS第1水準有2965字符，其中包括常用漢字1945字和其他人名常用漢字。JIS第2水準共3390字。JIS第3水準以及第4水準是不同行業所需要的專特殊符號。

以JIS第二水準漢字來說，很多華人地區常見中的中文字沒有，像是：危份伙你偷僱凳卡厝厲另吵呢咱哪唷啃嗎嗝嘍嚐圾垃塌墊增夠夯奶她屌崁崽巢幫憨懂扒扭扯拖揍揪搞摔摳撿擋攔旦晚晾曬朵查桌棵每汙沉淚渴災烘烤燙燜爸玫瘦皂眨眯睏綁綠緣耍脫腳褲趕趟踩軀醃醬陡雞餵餿鹼麵

### 5種字重(Style)

* ExtraLight
* Light
* Regular
* Medium
* Bold

原本的衡山毛筆行書字體放在Regular 字重 裡，透過程式自動產生ExtraLight、Light、Medium、Bold 新的字重。Light字重是把原本的衡山毛筆行書微微調細一點點。在ExtraLight的字重裡，可能會因為筆劃太細造成某些筆畫消失。在Medium和Bold的字重裡，可能會因為筆劃太粗造成某些筆畫重疊難以識別，有粗體字的需求，可以先挑戰使用Bold字重看看，如果發現效果不如預期，再改用Medium字重。

不能確定自動產生出來的字重裡每一個都是完整的字，畢盡程式會誤判是常有的事情，所以不是在Regular字重裡的筆劃可能會消失。

![正風毛筆字體](https://github.com/max32002/masafont/raw/master/preview/preview_style.png)

軟語的「語」補的不好，字太重。

### 清除衡山毛筆行書字體裡空白的文字

衡山毛筆行書字體裡有很多空白的字， 會造成無法讓系統自動用預設字體來補字，已清除空白的文字。

### 調整標點符號位置

衡山毛筆行書字體的全形標點符號針對日本做設計，調整為台灣常見的置中用法。半形的 backslash，調整為非日本地區用法。

### 增加部分臺灣口語、閩南語和客語中文字

例如：喵呣哖唚啥嗍嗝尪䆀魩


### 修改
* 原本的衡山毛筆行書字體「朧」，右邊的龍字有誤，少了三筆劃，已使用其他有筆劃的龍來替代。可能是原作者留下的彩蛋，在莫大毛筆字體裡也是相同的字，少了相同的筆畫。
* 原本的衡山毛筆行書字體「町」，右邊的丁字有誤，只剩下一半，已重新組字。
* 原本的「示」部和「礻」會交叉使用，看起來很奇怪，統一使用台標體的「礻」部。
* 原本的「食」，統一使用台標體的「食」，使用點，而不是橫筆。
* 原本的「偷喻愉揄渝瑜蝓諭踰輸鍮」，使用台灣常用的刂，而不是日本常用的《。另外新增：堬媮崳榆牏睮緰羭腧褕貐隃
* 原本的「高」寫法太日式，口的旁邊還有多條奇怪的直線，修改為比較通用的「高」。

## 下載字型

請點選GitHub此畫面右上綠色「Clone or download」按鈕，並選擇「Download ZIP」，或點進想下載的ttf字型檔案，再點「Download」的按鈕進行下載。

## 使用 WebFont

網路字型(Web Font)，用於網頁上的字型顯示，使用者的用戶端不需預先安裝字型檔，一樣能夠看到特殊的字型效果。實現該功能的原理是在瀏覽時才下載字型檔。

可以服用下面的css:
```
@font-face {
  font-family: masafont-Regular;
  src: url(https://github.com/max32002/masafont/raw/master/webfont/MasaFont-Regular.woff2) format("woff2")
  , url(https://github.com/max32002/masafont/raw/master/webfont/MasaFont-Regular.woff) format("woff");
}
```
您也可以透過從CDN引入在GitHub上woff2檔案的網址，再把上方的url()內容置換成CDN快取後的網址，將可大幅加快網頁載入。推薦使用 jsDelivr 的服務，在速度上挺不錯的，參考看看： www.cdnperf.com/#!performance,Asia 。

## 附註

* 補的缺字，由於缺乏設計美感，所以效果差強人意，但是聊勝於無。
* 歡迎一起來補字，如果您也有自己造字並且想更新到正風毛筆字體裡，請把您的ttf字型檔，透過email(weng.32002@gmail.com)給我，謝謝。由於Max是新手補字，難免補很略醜，如果您也挑戰修改了同一個字，也歡迎寄給我合併，當然您也可以另外再起一個新的字型名稱。
* 目前是Beta公測版本，歡迎提供測試反饋，請直接反饋在GitHub的Issues中。
* 日系字型，「者」會多一點，是正常的，第一次看到會覺得有點怪。
* 直接使用日系字體的字：「虛」用「虚」；「徵」使用「徴」；「粵」使用「粤」；「絕」使用「絶」；「閱」使用「閲」
* 沒有使用日系字體的字：「彥產」使用「文」而不是「立」。
* 沒有使用日系字體的字：「戶」不是「戸」；「麵」不是「麺」；「黑」不是「黒」；「德」不是「徳」；「歲」不是「歳」；「歷」不是「歴」；「曆」不是「暦」；「鄉」不是「郷」；「啟」不是「啓」；「娛」不是「娯」；「繫」不是「繋」


## 著作權與授權

* 本字型是基於改造畫法家青柳衡山先生所開發、發表的「[衡山毛筆フォント行書](https://opentype.jp/kouzangyousho.htm)」字型。
* 本字型基於 SIL Open Font License 1.1 授權條款免費公開，關於授權合約的內容、免責事項等細節，請詳讀 License 文件。
    * 可自由商用 不需付費、知會或標明作者，即可自由使用此字型，亦可做商業應用。
    * 可自由傳布 可自由分享檔案、將檔案安裝於任何軟硬體中。
    * 可自由改作為其他字型 將字型檔案修改重製為其他字型檔案，改作後的字型檔案須同樣依 Open Font License 釋出。

    
## 相關文章

* 獅尾XD珍珠 Swei.XD.Pearl
https://max-everyday.com/2020/07/swei-xd-pearl/
* 獅尾B2黑體 Swei B2 Sans
https://max-everyday.com/2020/07/swei-b2-sans/
* 獅尾B2宋朝 Swei B2 Serif
https://max-everyday.com/2020/07/swei-b2-serif/
* 獅尾D露西 Swei D Lucy
https://max-everyday.com/2020/07/swei-d-lucy/
* 台灣圓體 TaiwanPearl
https://max-everyday.com/2020/06/taiwanpearl/
* 獅尾肉丸 Swei Meatball
https://max-everyday.com/2020/06/swei-meatball/
* 獅尾四季春字體 Swei Spring
https://max-everyday.com/2020/04/swei-spring/
* 獅尾半月字體 Swei Gothic
https://max-everyday.com/2020/04/swei-half-moon/
* 獅尾圓體 Swei Gothic
https://max-everyday.com/2020/04/swei-gothic/
* 獅尾黑體 Swei Sans
https://max-everyday.com/2020/03/swei-sans/
* 內海字體 (NaikaiFont) 
https://max-everyday.com/2020/03/naikaifont/
* 莫大毛筆字體 (Bakudai)
https://max-everyday.com/2020/03/bakudaifont/
* 正風毛筆字體 (MasaFont)
https://max-everyday.com/2020/05/masafont/
* 清松手寫體 (JasonHandWriting)
https://jasonfonts.max-everyday.com/
* 源泉圓體
https://github.com/ButTaiwan/gensen-font
* jf open 粉圓
https://github.com/justfont/open-huninn-font
* 假粉圓體
https://github.com/max32002/FakePearl
* 俊羽圓體
https://github.com/max32002/YuPearl

## 相關影片
* [MaxCodeReview] FontForge 補字：石部 (正風毛筆字體)
https://www.youtube.com/watch?v=Or5pABnALZc

## 毛筆字體的應用範例

* 【故宮小劇場】跟著八段錦‧新‧洗武式 https://www.facebook.com/npmshops/posts/3311050418906629


## 贊助Max

很高興可以替中華民國美學盡一分心力，如果你覺得這篇文章寫的很好，想打賞Max，贊助方式如下：
https://max-everyday.com/about/#donate

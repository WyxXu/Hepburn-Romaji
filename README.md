# Hepburn-Romaji 黑本ローマ字



![image](https://github.com/WyxXu/MOBO-Hepburn-Romaji/assets/108942702/f6563018-99b0-47b3-bd89-12355d7cc718)



簡單説明
----


主要參考【ヘボン[Hepburn]式ローマ字[羅馬字 Romaji/Romanizatoin ]】，給日文假名全部標上發音。

字體以 フロップデザインフォント（flopdesignfont）的 モボ フォント 為基礎，增加了假名缺字。

源字體發佈地址：  モボ フォントset - フロップデザインフォント - https://flopdesign.booth.pm/items/4647262

MOBO是原字體，HepburneRomaji是我改的字體。

源字體也會在庫裏面放一份，以保留修改前的字體底本。如果需要原字體的話還是請到原作者的發佈頁下載。



字體效果演示：

![image](https://github.com/WyxXu/MOBO-Hepburn-Romaji/assets/108942702/22dd1981-8375-41b6-b972-160acfd298c2)

這樣就直接跳過識讀片假名，直接到猜英語原文是什麽的階段

發音表
----

![image](https://github.com/WyxXu/MOBO-Hepburn-Romaji/assets/108942702/5d36c1ed-eace-401b-a6b8-5f49b19a552b)
![image](https://github.com/WyxXu/MOBO-Hepburn-Romaji/assets/108942702/d389b42c-8266-4cf2-8380-0a984a43b453)
![image](https://github.com/WyxXu/MOBO-Hepburn-Romaji/assets/108942702/26123bc7-e98b-44df-8769-0ad778aeb18a)
![image](https://github.com/WyxXu/MOBO-Hepburn-Romaji/assets/108942702/7ea357fc-f92e-47db-859b-e57fc32db8d3)

* 半寬仮名未作標注，太窄了，標註放不下
* 変体仮名、新沖縄文字、台湾語仮名等未收錄（不考虑）
* 收錄已棄用的仮名 ゑ ゐ ヱ ヰ 𛀀 𛄡 𛄟 𛄢 𛄠 𛀁 𛀆 等
* 其他變體假名很少接觸得到，因而未收錄
* 收錄了一些用於尾音的小假名，比如 ㇷ゚	ㇳ	ㇰ	ㇺ ，因爲覺得偶爾可以用來拼寫方言
* ヵ ヶ視爲符號，不標註。雖然不知道有什麽用，但補了 ゕ ゖ，以和片假名對稱
* 不是所有發音都有平假名和片假名兩套，因爲現代日語有分工，非日語詞匯主要用片假名
表記發音，所以多數只能看到片假名用例。


Ｍiscellaneous
----

![image](https://github.com/WyxXu/MOBO-Hepburn-Romaji/assets/108942702/0136a59b-a87c-4dd6-92f7-6106cc70ad74)

按 MOBO 的風格畫了一個豆腐塊（U+fffd）


如何使用
----

直接安裝字體即可，無論是輸入還是複製黏貼，都會自動根據上下文調整發音標注

![image](https://github.com/WyxXu/MOBO-Hepburn-Romaji/assets/108942702/3f4d58d9-3864-4c43-ba63-9e997b914893)

https://www.tiktok.com/@weixhee/video/7241385845377223938?lang=en


瀏覽器中使用的的話 `shift-ctrl-C` 點擊某個層級的頁面元素，開控制台添加樣式：


```css
font-family: "MOBORE" !important;
line-height: 1.5em !important;
```

![image](https://github.com/WyxXu/MOBO-Hepburn-Romaji/assets/108942702/d07cab00-f944-4d3e-bb20-66995cac6123)


在推特等平臺使用可以搭配 瀏覽器插件 furigana，先將漢字標注上假名，再經字體給假名標注發音

![image](https://github.com/WyxXu/MOBO-Hepburn-Romaji/assets/108942702/7de3d838-84ac-42c6-972c-c12b6cd9a841)

![image](https://github.com/WyxXu/MOBO-Hepburn-Romaji/assets/108942702/e3874620-fb92-46f2-b0e3-7bffc8854e07)

![image](https://github.com/WyxXu/MOBO-Hepburn-Romaji/assets/108942702/825a7dc8-fd30-478d-acd0-5f4b1d6d41c6)

不確定展示他們的推文是否侵權……





注意：

* 不是所有平臺（不同的布局和字体渲染引擎）顯示效果都能达到預期
* 在　word 中如果不是　標準　，可能会导致　opentype 的 ligature 失效，進而發音標注錯誤
** ![image](https://github.com/WyxXu/MOBO-Hepburn-Romaji/assets/108942702/27c6b698-650e-4ce4-be30-aba118e1b87a)
* unicode 值四位數以上的字符在多數平臺顯示都可能出問題， 比如や𛀆1B006ゆ𛀁1B121よ ヤ𛄠1B120ユ𛄡1B001ヨ


第一次做字體，邊學邊做，有很多不成熟的地方。感謝字體群群主懶懶在字體知識方面的指導。

後續考慮製作其它文種的，比如愛爾蘭文和天城文。
接下來沒餓死，有閑功夫的話再説。

一直用 asciidoc，不會寫 markdown，沒閑工夫就不折騰了，凑合看吧。


以上



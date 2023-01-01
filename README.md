# Flex-Panel-Gallery
[DEMO](https://chihtsunglu.github.io/Flex-Panel-Gallery/flex.html)
## **CSS**
#### Box-sizing
- 針對盒模型(box-model)的設計：會將 padding 與 border  納入「高及寬」的計算
- 兩個值可以選：Content-box (預設值) 及 Border-box
- 用來解決跑板問題
- 這邊也用到「Inherit」繼承 parent 的 value
#### Panels
- 利用「overflow」hidden 屬性將滿版出來的選擇「隱藏」
- vh 代表的是view height，螢幕可視範圍高度的百分比
- 利用 Transition (https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions) 達到動畫效果
  - 需要利用 Javascript 做到事件觸發或是透過偽類別(hover)呈現效果
  - cubic-bezier(https://developer.mozilla.org/zh-TW/docs/Web/CSS/transition-timing-function) 控制動畫速度

#### Panel
- inset 將 Shadow 由 outset 改為 inset
#### nth-child
- 偽類選取器（pseudo class selector）
- 選取第 N 個 child ; 也可設定為 odd / even
#### first-child & last-child
- 利用`panel > *:first-child`選取選取第一個子物件`Hey`
- 利用`panel > *:last-child`選取最後一個子物件`Dance`
````html
<div class="panel panel1">
<p>Hey</p>
<p>Let's</p>
<p>Dance</p>
</div>
````

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
#### Panel
- inset 將 Shadow 由 outset 改為 inset
#### nth-child
- 偽類選取器（pseudo class selector）
- 選取第 N 個 child ; 也可設定為 odd / even

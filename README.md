如何使用
=====================================
開啟index.html


更動部分
=====================================

**index.html的優化**
1.將引用javascript的地方用async做異步處理

2.異步加載google font

3.將print用@media處理

4.將style.css中重要的部分內嵌入html中，並將針對移動裝置的部分用@media

5.壓縮圖片、並把原先用網址引用的圖片改為本地讀取並壓縮

6.壓縮css、html


**pizza網頁的優化(main.js)**
1.使用getElementBy()系列 取代 querySelector() 系列，提升速度

2.把changePizzaSizes()函數中導致強制同步的部分修正，把不必要的函數合併

3.把updatePositions)函數中導致強制同步的部分修正，將style.left改成使用style.transform，並把初始化位置的部分移到了生成披萨滑窗的地方

4.使用requestAnimationFrame優化pizza動畫

5.減少pizza數量



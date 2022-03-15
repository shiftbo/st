## 什么是BFC
    BFC 块格式化上下文 block formatting context 是web可视css渲染的一部分，是块盒子的布局过程中发生的区域，是浮动元素和其他元素交互的区域

##  怎么创建BFC

    1. 根元素 html
    2. 浮动元素 float:不是none;
    3. 绝对定位 position:absolute or fixed
    4. 行内块 display:inline-block
    5. 表格单元格 display:table-cell
    6. 表格标题 display:table-caption
    7. 匿名表格单元格元素 display:table table-row等
    8. overflow 不为visible
    9. display flow-root
    10. contain layout content paint
    11. display flex
    12. display grid
    13. column-count
    14. column-span
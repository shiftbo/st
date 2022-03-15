# 栅格布局  

    css中最强大的布局  
    唯一的二维布局 可以同时布局 行列
## 用法  

    设置栅格布局  
    display：grid 或者 display: inline-grid
    关键属性  
    grid-template-column 定义每一列的宽
    grid-template-rows 定义每一行的高
    grid-gap 栅格间距
    grid-auto-flow grid布局排列方式 column/row (dense填满空格)

    单元格内容位置
    justify-items 水平元素位于宫格位置
    align-items 垂直元素位于宫格位置
    place-items 合并写法

    整个内容位于栅格的位置
    justify-content 属性， 
    align-content 属性，
    place-content 属性
    


    repeat() 可以重复填充  auto-fill 自动无限填充
    
    grid-template单位 px像素、百分比、fr
    minmax()长度范围

## 对比flex布局  

    1.
Tooltip组件

1、outline 属性是在一条声明中设置多个轮廓属性的简写属性,例如 outline-style, outline-width 和 outline-color。

border 和 outline有如下区别：
outline不占据空间，绘制于元素内容周围。
outline 属性可使用以下一个、两个或三个值来声明，且顺序不重要。
根据规范，outline通常是矩形，但也可以是非矩形的。
```
/* 样式 */
outline: solid;

/* 颜色 | 样式 */
outline: #f66 dashed;

/* 样式 | 宽度 */
outline: inset thick;

/* 颜色 | 样式 | 宽度 */
outline: green solid 3px;

/* 全局值 */
outline: inherit;
outline: initial;
outline: unset;
```

2、white-space（CSS）属性是用来设置如何处理元素中的空白。

normal：连续的空白符会被合并，换行符会被当作空白符来处理。换行在填充「行框盒子(line boxes)」时是必要。

nowrap：和 normal 一样，连续的空白符会被合并。但文本内的换行无效。

pre：连续的空白符会被保留。在遇到换行符或者`<br>`元素时才会换行。 

pre-wrap：连续的空白符会被保留。在遇到换行符或者`<br>`元素，或者需要为了填充「行框盒子(line boxes)」时才会换行。

pre-line：连续的空白符会被合并。在遇到换行符或者`<br>`元素，或者需要为了填充「行框盒子(line boxes)」时会换行。


3、z-index 属性设定了一个定位元素及其后代元素或 flex 项目的 z-order。 
当元素之间重叠的时候， z-index 较大的元素会覆盖较小的元素在上层进行显示。

属性指定：盒子在当前堆叠上下文中的堆叠层级；盒子是否创建一个本地堆叠上下文。

取值：
auto：盒子不会创建一个新的本地堆叠上下文。在当前堆叠上下文中生成的盒子的堆叠层级和父级盒子相同。

<integer>（整型数字）：是生成的盒子在当前堆叠上下文中的堆叠层级。此盒子也会创建一个堆叠层级为 0 的本地堆叠上下文。这意味着后代（元素）的 z-indexes 不与此元素的外部元素的 z-indexes 进行对比。


4、calc(),此 CSS 函数允许在声明CSS属性值时执行一些计算,可以是采用标准操作符处理法则的简单表达式。
  
它可以用在如下场合：`<length>、<frequency>, <angle>、<time>、<percentage>、<number>、或 <integer>。`
  
表达式中的运算对象可以使用任意 <length> 值。在需要时，你可以在一个表达式中混用这类值的不同单位,还可以使用小括号来建立计算顺序。
  
`+` 和 `-` 运算符的两边必须要有空白字符。
  
  比如，calc(50% -8px) 会被解析成为一个无效的表达式，解析结果是：一个百分比 后跟一个负数长度值。
  
  加有空白字符的、有效的表达式 calc(8px + -50%)会被解析成为：一个长度 后跟一个加号 再跟一个负百分比。
  
`*` 和 `/` 这两个运算符前后不需要空白字符，但如果考虑到统一性，仍然推荐加上空白符。
  
5、onmouseenter：
  https://www.runoob.com/try/try.php?filename=tryjsref_onmousemove_over_enter
  
onmouseenter， 元素绑定了监听事件后，当一个指针设备（通常是鼠标）移动到这个元素上时mouseenter事件将会被触发。该事件通常与 onmouseleave 事件一同使用, 在鼠标指针移出元素上时触发。

onmousemove, onmouseenter 和 mouseover 事件的不同:

onmousemove 事件在鼠标移动到 div 元素上时触发。

mouseenter 事件中有在鼠标指针进入 div 元素时触发。

onmouseover 事件在鼠标指针进入 div 元素时触发,在子元素上也会触发(p 和 span)。

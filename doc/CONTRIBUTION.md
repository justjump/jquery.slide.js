#CONTRIBUTION

首先，很感谢你有打算为jquery.slide.js贡献代码。请采用fork + pull request 方式，并在发起pr前先将master上超前的代码rebase到自己的分支上。

##注意事项
###可修改的文件
可修改的文件只有src/jquery.slide.js 以及 src/jquery.slide.css。

###保持修改的代码是最新的
修改前请替换成站上最新的代码，如果看到Pull Request里面有旧代码且不加说明的一律拒绝。

###不要添加太多冷门的功能
根据最初的打算，压缩版的代码大小不能超过10KB。我们的目标是轻量与高效，所以要使用冷门的功能，请考虑使用[Swiper](http://www.swiper.com.cn/)。我们后期也有打算暴露方法，让开发者自己设计功能。

##代码规范
###src/jquery.slide.js
####符号：
1. 以下符号两端要加空格：(1)'=', (2)'+', (3)'-', (4)'*', (5)'/', (6)'+=', (7)'-=', (8)'&&', (9)'||', (10)'===',
   三目运算中的(11)'?'和(12)':'（如果条件和结果分三行写，'?'和':'右侧的空格可以不要）；
2. 以下符号只需要在后面加空格：(1)':', (2)','（逗号后面断行的可以不用）；
3. 以下符号只要在前面加空格： (1)'++', (2)'--'；
4. if，else，function和for括号的后面的'{'符号之前要加空格；
5. 其他符号前后都不用加空格；

####ECMAScript部分：
1. 循环只用for循环，不用while和do...while；
2. if...else语句中的else前面要加空格；
3. 相等判断请使用三个等号‘===’而不是两个等号‘==’；
4. 最外层引号是单引号；
5. 常量请使用全部字母大写，用下划线相连的格式；
6. 每个语句后面都要加分号；
7. 过长的代码请分行书写；
8. 一个语句里面定义多个变量，请分行对齐书写；
9. 两个相邻的function之间要空一行；
10. 代码缩进4个空格或tab；
11. 嵌套不要太深，请适当使用return；
12. 所有对象字面量的键名不要加引号；

####jQuery部分：
1. jQuery变量之前要加'$'；
2. 变量是对象字面量的，每个属性要另起一行；
#### 注释：

1. 参数和变量的注释要对齐；
2. 单行注释请使用双斜杠，多行注释使用方式如下：
```javascript
/**
 * Detecting mousewheel scrolling
 *
 * http://blogs.sitepointstatic.com/examples/tech/mouse-wheel/index.html
 * http://www.sitepoint.com/html5-javascript-mouse-wheel/
 */
```

####其他：

1. 所有非原型的方法请写在function Slide(){}和原型方法之间；
2. 所有错误检测请写在 function errorDetection(){}里面。



### src/jquery.slide.css

1. 属性名和属性值之间的冒号右边要加空格；
2. 每一条属性另起一行书写；
3. 选择器与‘{’符号同行，中间空一格，'}'符号另起一行；
4. 属性缩进4个空格或tab。
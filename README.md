# 前端研讨课作业
## 一、前言
课上我们分别介绍了前端的三层：`HTML`，`CSS`，`JavaScript`。了解了 `HTML` 中常用的标签及其属性、`CSS` 中常用的属性、`JavaScript` 中的基础语法和它们结合使用的方式。在 `example` 文件夹中我们提供了相关的示例供参考，各示例文件所相关的内容在 `ppt` 中标注了出来。
![](https://tva1.sinaimg.cn/large/008i3skNly1gvsqadf7a3j315m0mgadx.jpg)

本次作业将分别练习 `HTML`，`CSS`，`JavaScript` 以及他们的结合使用，帮助同学们进一步了解和掌握前端开发的基本思路和技术。

## 二、开发方式
开发时有在线和本地两种方式可选择。
### 2.1 查看代码
使用记事本或其它编辑器（如：[`VScode`](https://www.jianshu.com/p/51dfbe2c9583)）打开 `homework.html` 即可查看代码。

### 2.2 在线开发（推荐）
将 `homework.html` 中的代码复制到[在线工具](https://c.runoob.com/front-end/61/)的 `HTML` 部分，即可开始在线开发。如下图：
![](https://tva1.sinaimg.cn/large/008i3skNly1gvsrbvdq5hj31ne0u078g.jpg)

<span style="color: red; font-weight: bold;">注意</span>：中途退出网页或开发完成后请及时将代码复制到本地的 `homework.html` 中，该在线工具不会保存代码。

### 2.3 本地开发
#### 2.3.a 代码编写
使用记事本或 [`VScode`](https://www.jianshu.com/p/51dfbe2c9583) 等编辑器打开 `homework.html` 即可开始编写代码。相比之下，`VScode` 等代码编辑器提供的拼写提示、自动补全等功能将大大方便开发。

#### 2.3.b 实现效果查看
在查看我们实现效果时，我们只需要用浏览器打开我们编写的 `HTML` 文件即可。

建议使用 [Google Chrome](https://www.google.com/intl/zh-CN/chrome/) 浏览器。

## 三、作业提交方式
本次作业的提交⽅式仍然以 `Git` 的形式进⾏提交，即提交 `Git` 仓库的链接。`Git` 课程的作业中同学们都建⽴了⾃⼰的 `Git` 仓库，本次作业同学们在已经建好的仓库中建立一个文件夹 `FrontEndHomework`，并将编写好的 `homework.html` 文件放入其中。示例仓库见[链接](https://git.tsinghua.edu.cn/zengz21/innovationsw)，如下图
![](https://tva1.sinaimg.cn/large/008i3skNly1gvss51vlwij31hy0fuwg5.jpg)

## 四、作业题目
在本次作业中我们将逐步实现一个简单的加法计算器
### 4.1 `HTML` 练习
1. 将页面中 `YourName` 和 `20xxxxxxxx` 处修改为你自己的信息；  
2. 在你的信息下面添加一条分割线；  
3. 在分割线下方添加一个元素 `0`，其 `id` 设置为 `result`；  
4. 在 `0` 下方添加一个符号 `+`；  
5. 在 `+` 下添加三个元素，分别为 `1`, `2`, `3`，要求它们在同一行，且他们的类（class）设置为 `btn`；  
6. 在 `1`, `2`, `3` 下添加三个元素，分别为 `4`, `5`, `6`，要求它们在同一行，且他们的类（class）设置为 `btn`；  
7. 在 `4`, `5`, `6` 下添加三个元素，分别为 `7`, `8`, `9`，要求它们在同一行，且他们的类（class）设置为 `btn`；  
8. 在 `7`, `8`, `9` 下添加一个元素 `0`，他的类（class）设置为 `btn`。

效果如图：
![](https://tva1.sinaimg.cn/large/008i3skNly1gvstca6kw5j31a20cojs0.jpg)

**提示**：参考标题、姓名和学号的实现。`<div></div>` 标签会换行，而 `<span></span>` 不会。

### 4.2 `CSS` 练习
1. 将 4.1.3 中的 `0` 的样式设置如下：
   1. 字号（`font-size`）设置为 `30px`
   2. 装饰（`text-decoration`）设置为下划线（`underline`）
2. 将 4.1.4 中的 `+` 设置为红色；
3. 将类（class） `btn` 的样式设置如下：
   1. 字体（`font-family`）的值设置为 `'Courier New', Courier, monospace`
   2. 鼠标箭头属性（`cursor`）属性设置为手型光标（`pointer`）
   3. 设置 `2px` 宽的实线（`solid`）黑色（`black`）边框（`border`）
   4. 行高（`line-height`）设置为 `40px`
   5. 内边距（`padding`）上、下、左、右分别为 `5px`, `5px`, `10px`, `10px`

效果如图：
![](https://tva1.sinaimg.cn/large/008i3skNly1gvstqfuagbj319q0hmq3r.jpg)

**提示**：参考标题、姓名和学号的实现，如何设置 `class`、`id` 及其样式。

### 4.3 `JavaScript` 练习
为 4.1.5-8 中的元素 `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `0`，添加点击事件（`onclick`），使得当点击他们时，4.1.3 中的 `0` 增加所点击的数。

如，首先点击 `1`，则 `+1` 变成 `1`，再点击 `7`，则 `+7` 变成 `8`。

效果如图：
![](https://tva1.sinaimg.cn/large/008i3skNly1gvstxx25s6j31940hq3zg.jpg)

**提示**：参考 `js-html.html` 中 `add()` 函数的实现。本题各元素所调用的函数应该是同一个，仅传入的参数不同。

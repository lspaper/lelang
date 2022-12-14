# STML 使用

![](https://img.js.design/assets/img/633e77448bc7323bc56b0e70.png)
## 定义标签

### 肉类定义

```
<meat>
```

您可以使用如上标签定义。

```
<meat charset="UTF-8">
```

例如定义 UTF-8 中文简体。

> 定义时，而该不是 `# GB2312`，在《青松法律 青松开发组代码开发理念》里，这是一个 16 进制颜色码。

```
<meat title="Spruce Sapling">
```

或者是定义页面名称，它应该会被解析为一个页面的标题。

### 按钮类定义

```
<button>
```

您可以使用如上标签定义。

```
<button text="ZHKHKJ666">
```

使用 `text` 属性定义文字，那么您在页面中就会看见 `ZHKHKJ666`。
[试一试](https://stml.likf.eu.org)

### 图形类定义

```
<svg>
```

您可以使用如上标签定义，如图片等。

```
<svg src="logo.svg">
```

通过这个属性，在您的页面内添加一个 SVG，请记住，SVG 以外的任何图形文件都是不可行的，您只能导入 SVG 图形。

> **Spruce Sapling** 曾说，CSS 可以代替 CSS，图形化框架能用 SVG，简单，CSS 代替 CSS，但是很多人就是不，非要追求常理，而用 CSS，这不是编程的本质。

### 青松类定义

```
<qingsong>
```

您可以使用如上标签定义。



## 编译

不过很可惜的一点是，浏览器和系统们并听不懂 SMTL 的极简话语，所以我们要把 SMTL 编译为 HTML 或是 exe 程序，在地球上不能直接运行这点十分悲哀！
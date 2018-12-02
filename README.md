### HTML5
#### 基本标签介绍

|标签|说明|
|------|------|
|`<!--...-->`|注释|
|`<html>`|根元素，允许完全忽略这个元素|
|`<head>`|页面头部分，允许完全忽略这个元素|
|`<title>`|页面标题|
|`<body>`|页面主题部分，可以指定通用属性：id、class、style；可以指定事件属性：onload、onunload、onclick、ondblclick、onmousedown、onmouseup、onmouseover、onmousemove、onmouseout、onkeypress、onkeydown、onkeyup 这些属性用于指定JavaScript脚本|
|`<h1>`到`<h6>`|定义标题1到标题6|
|`<p>`|定义段落，该元素可以指定 id、class、style、dir、title 等通用属性，还可以指定onclick等各种事件属性；只能包含文本、图像、超链接、文本格式化元素和表单控件元素等内容；可以包含span|
|`<br>`|插入一个换行，可以指定通用元素id、class、style|
|`<hr>`|定义水平线，可以指定通用元素id、class、style、；可以使用事件属性：onclick|
|`<div>`|定义文档中的节；可以指定通用属性：id、class、style、dir、title；指定事件属性：onclick；可以包含p、span、h1~h6、form、table、列表元素、div|
|`<span>`|与div基本相似，区别是span只是表示一段一般性文本，该元素包含的文本内容默认不会换行，该元素可以指定和div相同的属性； 只能包含文本、图像、超链接、文本格式化元素和表单控件元素等内容；不能包含p|
|`<b>`|定义粗体文本，可以指定id、class、style、dir、title等通用属性，可以指定事件属性：onclick|
|`<i>`|指定斜体文本，该元素可以指定id、class、style、dir、title等通用属性，还可以指定onclick等各种事件属性|
|`<em>`|定义强调文本，实际效果和斜体文本差不多，可以指定id、style、class、dir、title、onclick|
|`<strong>`|定义粗体文本，一般代表重要文本|
|`<small>`|小号字体文本，可以指定id、class、style、dir、title、onclick|
|`<sup>`|定义上标文本，可以指定id、class、style、dir、title、onclick|
|`<sub>`|定义下标文本，可以指定id、class、style、dir、title、onclick|
|`<bdo>`|定义文本显示的方向，可以指定id、class、style、dir、title、onclick、除此之外，该元素应该指定dir属性，该属性值只能是ltr或rtl，用于指定文本的排列方向|
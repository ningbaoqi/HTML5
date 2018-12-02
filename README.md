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
|`<abbr>`|用于表示一个缩写，使用它时，建议使用title属性，该属性用于指定该缩写所代表的全称|
|`<address>`|用于表示一个地址|
|`<blockquote>`|定义一段长的引用文本，可以指定cite属性，该属性用于指定该引用文本所引用的网址URL或出处；换行长文本|
|`<q>`|定义一段短的引用文本，不换行短文本|
|`<cite>`|用于表示作品(一本书，一部电影，一首歌)的标题|
|`<code>`|用于表示一段计算机代码|
|`<dfn>`|用于定义一个专业术语|
|`<del>`|定义文档中被删除的文本；可以使用属性：cite：该属性值为一个URL；datetime：定义文本被删除或插入的日期、时间|
|`<ins>`|定义文档中插入的文本；可以使用属性：cite：该属性值为一个URL；datetime：定义文本被删除或插入的日期、时间|
|`<pre>`|表示该元素所包含的文本已经进行了预格式化|
|`<samp>`|用于定义示范文本内容|
|`<kbd>`|用于定义键盘文本|
|`<var>`|用于表示一个变量|
|`<a>`|定义超链接，可以指定：id、class、style、dir、title、onclick等：href：指定超链接所链接的另一个资源；hreflang：指定超链接所链接的文档所使用的语言；target：指定使用框架集中的哪个框架来装载另一个资源，属性值可以是：_self：使用自身，_blank：新窗口：_top：顶层框架：_parent：父框架；download：用于让用户下载目标链接所指向的资源，而不是直接打开该目标资源；type：指定被链接文档的MIME类型；media：指定目标URL所引用的媒体类型，默认值是all|
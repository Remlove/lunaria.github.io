@ -1,68 +0,0 @@
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>First</title>
</head>
<body>
<h3 id="one">锚点链接示例：（代码49行）</h3>
    <h3 id="two"> </h3>
<h1>一级标题</h1>
<h2>二级标题</h2>
<h3>三级标题（共6级，以此类推）</h3>
<p>段落标签 段落1（段落后面自动空一行）</p> <p>段落标签 段落2</p>
<br 换行标签，如果一句话中遇到此标签，自动换行。段落间空间较大，而换行后，两行之间没有空余/>
这是 <strong>加粗</strong> 标签         <br />
这也是 <b>加粗</b> 标签                 <br />
这是 <i>倾斜</i> 标签                   <br />
这是 <del>删除线</del> 标签             <br />
这也是 <s>删除线</s> 标签               <br />
这是 <ins>下划线</ins> 标签             <br />
这也是 <u>下划线</u> 标签               <br />
<div>盒子标签：div标签，一人占一行  a占一行</div>
<div> b也占一行</div>
<span>盒子标签：span标签，只占一点点  a</span>
<span>b</span>
<span>c</span>                      <br />
<h4>图像标签src：(标题标签单独占一行，且有加粗效果) src后键入图片路径</h4>
<img src="img 1.png"/>
<h4> alt：(图片无法正常显示时显示替换的文字)</h4>
<img src="img1.png" alt="替换文字"/>
<h4> title：(鼠标放到图片上，提示文字)</h4>
<img src="img 1.png" title="天气之子（提示文字）"/>
<h4> width：(设置图片宽度（像素）)</h4>
<img src="img 1.png" width="100"/>
<h4> height：(设置图片高度（像素）)</h4>
<img src="img 1.png" height="100"/>
<h4> 同时设置宽度和高度</h4>
<img src="img 1.png" width="200" height="100"/>
<h4> border:设置图片边框</h4>
<img src="img 1.png" width="100" height="100" border="20"/>
<h4> href:超链接标签(以http://开头，否则404) target(超链接打开方式，_self：覆盖本窗口，_blank新窗口打开)</h4>
<a href="https://www.google.com" target="_parent">谷歌(可替换为图片)</a> <a href="https://www.baidu.com" target="_blank"> 百度</a>
<h4> 内部链接</h4>
<a href="neibu/内部链接示例.html" target="_self">内部链接示例</a>
<h4> 空链接</h4>
<a href="#" target="_blank">空链接示例</a>
<h4> 下载链接（把链接内容换成文件路径即可，，不过是.exe或者.zip等压缩文件）</h4>
<a href="img 1.rar">下载链接示例</a>
<h4> 锚点链接，点击链接后可以快速跳转到本页面中的对应位置</h4>
<a href="#one">锚点链接示例</a>      <br />
<a href="#two">锚点链接示例：返回顶部</a>
<h4>注释标签</h4>
<!--注释，快捷键：Ctrl+/-->
空格：&nbsp;&nbsp;&nbsp;&nbsp;6
<h4>表格标签,tr表示行,td表示单元格,th表头单元格(其中文本加粗居中)</h4>
<table align="center" border="1" cellpadding="20" cellspacing="0"> <!--align:定义表格位置,cellpadding:单元格与内容间的空白像素，cellspacing:单元格与单元格间的空白像素
rowspan跨行合并，colspan跨列合并-->
    <thead><th>姓名</th>    <th>性别</th>    <th>年龄</th> </thead></tr>
    <tbody>
    <tr><td>a</td>    <td>man</td>    <td>1</td> </tr></tr>
    <tr><td>b</td>     <td>woman</td> <td>2</td> </tr></tr>
    <tr><td>c</td>     <td>man</td>   <td>3</td> </tr></tr>
    <tr><td rowspan="2">跨行</td>     <td colspan="2">跨列</td> </tr>
    <tr>    <td>man</td>   <td>3</td> </tr></tr>
    </tbody>
</table>
</body>
</html>

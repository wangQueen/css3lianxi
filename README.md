# css3lianxi
css3练习

## css3选择器

1.  css3后代选择器
	.list li:only-child
	选中list中作为唯一一个的li的子元素存在。
	.list :only-child
	选中list中的只有唯一一个子元素的元素。

3. 伪类选择器
	- :focus 匹配获取焦点的input元素
	- :first-letter 获取p标签的第一个文字
	- :first-line 匹配p标签的第一行文字
	- :before 在标签的内容之前添加内容，可以用来清除浮动。只能写文字
	- :after 在元素的内容之后插入内容，
、、、css
/*清除浮动*/
	.clf:after,.clf:before{
	content:"";
	display:block;
	clser:both;
}
、、、

> 2.做一些效果 “” 加一些图标。


4. 属性选择器
- [attr] 选中attr属性的所有元素；
- [attr=value] 选中attr属性=value的元素；
- [attr~flower]  选择 attr 属性包含单词 "flower" 的所有元素;（包含的是一个词）
5. 伪类选择器
- :enabled 选择每个启用的input元素

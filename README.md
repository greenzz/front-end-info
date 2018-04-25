HTML Questions:
1.What does a doctype do?
<!DOCTYPE> 声明必须是 HTML 文档的第一行，位于 <html> 标签之前。
<!DOCTYPE> 声明不是 HTML 标签；它是指示 web 浏览器关于页面使用哪个 HTML 版本进行编写的指令。
在 HTML 4.01 中，<!DOCTYPE> 声明引用 DTD，因为 HTML 4.01 基于 SGML。DTD 规定了标记语言的规则，这样浏览器才能正确地呈现内容。HTML5 不基于 SGML，所以不需要引用 DTD。
2.What are data- attributes good for?
data-是html5的新属性。这种方式通过访问一个元素的 dataset 属性来存取 data-* 自定义属性的值。这个 dataset 属性是HTML5 JavaScript API的一部分，用来返回一个所有选择元素 data- 属性的DOMStringMap对象。

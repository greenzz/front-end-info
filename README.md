HTML Questions:</br>
1.What does a doctype do?</br>
<!DOCTYPE> 声明必须是 HTML 文档的第一行，位于 <html> 标签之前。</br>
<!DOCTYPE> 声明不是 HTML 标签；它是指示 web 浏览器关于页面使用哪个 HTML 版本进行编写的指令。</br>
在 HTML 4.01 中，<!DOCTYPE> 声明引用 DTD，因为 HTML 4.01 基于 SGML。DTD 规定了标记语言的规则，这样浏览器才能正确地呈现内容。HTML5 不基于 SGML，所以不需要引用 DTD。</br>
  
2.What are data- attributes good for?</br>
data-是html5的新属性。这种方式通过访问一个元素的 dataset 属性来存取 data-* 自定义属性的值。这个 dataset 属性是HTML5 JavaScript API的一部分，用来返回一个所有选择元素 data- 属性的DOMStringMap对象。</br>

3.Consider HTML5 as an open web platform. What are the building blocks of HTML5?</br>
more semantic text markup</br>
new form elements</br>
vedio and audio</br>
new javascript API</br>
canvas and SVG</br>
new communication API</br>
geolocation API</br>
web worker API</br>
new data storage</br>

4.Describe the difference between a cookie, sessionStorage and localStorage.</br>
cookie,sessionStorage,localStorage都存储在客户端。每次客户端对服务器请求，cookie的
内容都会重新发送回服务器端,cookie会话期内有效，亦可以设置cookie的过期时间。sessionStorage在一个会话期间内有效，同一个窗口打开时可以读取该窗口内的sessionStorage,不同窗口或窗口关闭后重新打开窗口原来的sessionStorage无效。localStorage 一直有效，除非主动删除。

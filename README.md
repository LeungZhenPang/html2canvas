# html2canvas
利用 html2canvas 将 html 元素生成图片</br>
[html2canvas官网](http://html2canvas.hertzen.com/)

## 用法
##### 1.引入 html2canvas.js
```javascript
<script src="https://cdn.bootcss.com/html2canvas/0.5.0-beta4/html2canvas.js"></script>
```
##### 2.使用方法
```javascript
//两个参数：所需要截图的元素id，截图后要执行的函数， canvas为截图后返回的最后一个canvas
 html2canvas(document.getElementById('id')).then(function(canvas) {document.body.appendChild(canvas);});
 ```

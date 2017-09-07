# canvas-nest.js
来源：https://github.com/hustcc/canvas-nest.js  改进：支持在指定元素内生效
# 使用
1.在`</body>`前引用js文件
```html
<script type="text/javascript" src="canvas-nest.js"></script>
```
**2.指定要生效的元素ID`id=nest`**
例如：
```html
<body id="nest">
</body>
```
# 配置项
- color: 线条颜色, 默认: '0,0,0' ；三个数字分别为(R,G,B)，注意用,分割
- opacity: 线条透明度（0~1）, 默认: 0.5
- count: 线条的总数量, 默认: 150
- zIndex: 背景的z-index属性，css属性用于控制所在层的位置, 默认: -1
- ** eId:元素ID，默认：nest **
例如：
```html
<script type="text/javascript" color="0,0,0" opacity='0.5' count="150" zIndex="-1" eId="abc" src="canvas-nest.min.js"></script>
//此处eid="abc",这需要在设置对应元素的id="abc"
```

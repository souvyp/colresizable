jQuery可调整表和列宽插件-colResizable 
===============

###最基本的例子

#### 引入JS

```html
<script src="js/jquery-1.8.0.min.js" type="text/javascript"></script>
<script src="js/colResizable-1.6.js" type="text/javascript"></script>
```

#### TABLE

```html
<table class="table table-bordered">
<thead>
	<tr>
	   <th>栏目类型</th>
	   <th>活动名称</th>
	   <th>状态</th>
	   <th>操作选项</th>
	</tr>
</thead>
<tbody>
	<tr>
	   <td>青春日记</td>
	   <td>我们一起傻逼的日子</td>
	   <td>提交</td>
	   <td>审核</td>
	</tr>
	<tr>
	   <td>我和孩子的成长故事</td>
	   <td>成长故事</td>
	   <td>通过</td>
	   <td>审核</td>
	</tr>
</tbody>
</table>
```

#### JS

```js
<script type="text/javascript">
	$(function() {
		$("table").colResizable();
	})
</script>
```

以上步骤即可实现最简单的鼠标拖动调整表格列宽

在线演示：http://blog.itmyhome.com/colresizable/

更多信息参考：http://www.bacubacu.com/colresizable/
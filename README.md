ArrayList API:

下载<br>
	npm install arraylists

>引用包
```javascript
	let ArrayList = require("arraylists");
```

>创建一个ArrayList对象
```javascript
	let list = new ArrayList();
```

>添加一个元素
```javascript
	list.add(item);
```

>添加多个元素
```javascript
	list.add(item1,item2,item3...);
```

>删除指定元素
```javascript
	list.remove(item);
```

>删除多个元素
```javascript
	list.removeAll(item1,item2,item3...);
```

>清空集合元素
```javascript
	list.clear();
```

>深克隆一个集合
```javascript
	let list2 = list.clone();
```

>检查集合中是否包含指定元素
```javascript
	let bool = list.contains(item);
```

>获取指定位置上的元素
```javascript
	let temp = list.get(index);
```

>返回此列表中首次出现的指定元素的索引，或如果此列表不包含元素，则返回 -1
```javascript
	let index = list.indexOf(item);
```

>判断集合是否为空
```javascript
	let bool = list.isEmpty();
```

>用指定的元素替代此列表中指定位置上的元素
```javascript
	list.set(index,item);
```

>遍历集合
```javascript
	list.forEach(e => {
		let key = e.key;
		let value = e.value;
	});
```

>获取元素中第一个元素
```javascript
	list.first();
```

>获取元素中最后一个元素
```javascript
	list.last();
```

>返回元素字符串表现形式
```javascript
	list.toString();
```

关于作者:<br>
	email:admin@w3c.top
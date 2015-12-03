# for-of

## 萌芽时代

* 遍历数组

```
for (var i = 0; i < array.length; i++) {
    //TODO
    array[i]
}
```

##es5时代

```
array.forEach(function(value) {
    //TODO
    value
});
```

> 简洁 
> 
> 不能使用break 和 return 语句返回到外层函数

## for-in 

```
for (var index in ['aa', 'bb', 'cc']) {
    index // '1', '2'
}
```

> index 值是字符串 
> 代码按随机顺序遍历 
> 适用对象遍历

## es6

```
for (var value of array) {
    // TODO
    value
}
```

```
for (var [key, value] of array) {
    // TODO
    key 
    value
}
```

> 简洁
> 
> 避开for-in缺陷 
> 
> 正常响应 break、continue、return 
> 
> 也可以遍历字符串

```
for (var chr of  'sdfsdf') {
    chr
}
```

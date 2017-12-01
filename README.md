## 样式重置

```
对工作中基本用到的重置进行了汇总；
margin  padding值未用通配符* -这样可以增加浏览器渲染能力；不必须全部查找
```
## 移动端1px线的问题处理；


```
在web发展的今天；如今移动端的昌盛，也流出了很多各式各样的设备尤其是安卓手机；屏幕尺寸没有规范；
设备的物理像素、分辨率比例不一；导致1px线翻倍
```

# 1px线的使用

```
	在页面中（html）添加meta标签---内容的宽=设备的宽不允许缩放--如下
	<meta name="viewport" user-scalable="no" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
```

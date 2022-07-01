# wRC
简单好用的HTML通用Flex布局

<br>
###说明
"__w__"为前缀，用于区分用户的css class
"__R__"-row 代表横向
"__C__"-column 代表纵向
"__H__"-horizontal 代表水平方向
"__V__"-vertical 代表垂直方向
"__S__"-start 代表头部
"__C__"-center 代表中间
"__E__"-end 代表尾部
"__B__"-block 代表块(不加则默认宽度为100%)

默认width: 100%，当不需要100%宽度时，可以添加"__B__"取消宽度属性

<br>
###用法举例
"__w__"为前缀，必需添加。然后根据需求选择"__R__"或者"__C__"，之后用"_"分割后续布局要求。

例如：
"__wR_HC__" 横向布局-水平居中

```html
<div class="wR_HC">
    <span>水平居中</span>
</div>
```
---

默认宽度为100%，若不需要则在末尾添加"__B__"

例如：
"__wR_HCB__" 横向布局-水平居中-块
```html
<div class="wR_HCB">
    <span>水平居中-宽度以子元素大小为准</span>
</div>
```
---

"__wR_HCVC__" 横向布局-水平居中-垂直居中
```html
<div class="wR_HCVC">
    <span>水平居中-垂直居中</span>
</div>
```

---

使用"__C__"标识代表*纵向布局*

"__wC_HC__" 纵向布局-水平居中
```html
<div class="wC_HC">
    <span>水平居中</span>
</div>
```

<br>
### 代码示例
查看index.html即可


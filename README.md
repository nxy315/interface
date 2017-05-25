# 怎么使用MD


## 标题

`#是大标题`，`##，###以此类推`

## 列表

段前面加`-我是空格`就可以变成列表
- 我最酷
- 还是我最酷
- 我还是最酷
1. China NO.1
1. China NO.2
1. China NO.3
1. China NO.10000

## 链接

中括号接url`[我是链接](http://xxx)`
[草榴](https://github.com/nxy315)

## 注释

段前面加`>`,后面接文本
> 这就是一段注释

## 插入图片

叹号加中括号接地址 `![](httpxxx)`

![](https://avatars3.githubusercontent.com/u/16378539?v=3&s=460)

## 插   入   bash

方法````bash ````

```bash
sudo chmod ugo=rwx db

sudo ln -s /home/nxy/download/node/bin/node /etc/bin/node
sudo ln -s /home/nxy/download/node/bin/npm /etc/bin/npm
```

## 插   入   html

方法````html ````

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>
    ......
    ...
  </body>
</html>
```

## 插   入   js

方法````js ````

```js
let arr1 = ['a','b','c','d'];
let arr2 = [1,4];
arr1.filter((value,index)=>{
    return arr2.indexOf(index) === -1;
});
```

## 插   入   css

方法````css ````

```css
.content{
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  display: flex;
}
```

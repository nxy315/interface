# use markdown


## 标题

`#空格`
`##空格`

## 列表

无序列表 `-空格`
有序列表 `1.空格`

- 我最酷
- 还是我最酷
- 我还是最酷
1. China NO.1
1. China NO.2
1. China NO.3
1. China NO.10000

## 链接

中括号接url `[我是链接](http://xxx)`
[草榴1024](https://github.com/nxy315)

## 注释

`>空格`
> 这就是一段注释

## 字体加粗

`两边 **`

**我很粗**

## 插入代码

`bash`

```bash
sudo chmod ugo=rwx db

sudo ln -s /home/nxy/download/node/bin/node /etc/bin/node
sudo ln -s /home/nxy/download/node/bin/npm /etc/bin/npm
```


`html`

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


`js`

```js
let arr1 = ['a','b','c','d'];
let arr2 = [1,4];
arr1.filter((value,index)=>{
    return arr2.indexOf(index) === -1;
});
```


`css`

```css
.content{
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  display: flex;
}
```

## 插入图片

叹号加中括号接地址 `![](httpxxx)`

![](http://wx3.sinaimg.cn/large/006m97Kgly1fbr5gni087j30k00qdtd4.jpg)

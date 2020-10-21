面试题：使用css实现一个自适应浏览器大小，宽高比为2:1的布局

### 方法一

```js
<div>
  <span></span>
</div>
```

```css
div{
  position: relative;
  width: 100%;
  height: 0;
  padding-bottom: 50%;
}

span{
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
}

```

### 方法二

```css
div{
  width: 100vw;
  height: 50vw;
}

```

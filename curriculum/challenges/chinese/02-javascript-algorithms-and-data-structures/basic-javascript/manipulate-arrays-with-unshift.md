---
id: 56bbb991ad1ed5201cd392ce
title: 使用 unshift() 操作数组
challengeType: 1
videoUrl: 'https://scrimba.com/c/ckNDESv'
forumTopicId: 18239
---

# --description--

你不仅可以`shift`（移出）数组中的第一个元素，你也可以`unshift`（移入）一个元素到数组的头部。

`.unshift()`函数用起来就像`.push()`函数一样, 但不是在数组的末尾添加元素，而是在数组的头部添加元素。

# --instructions--

使用`unshift()`函数把`["Paul",35]`加入到`myArray`的头部。

# --hints--

`myArray`应该包含\[["Paul", 35], ["dog", 3]]。

```js
assert(
  (function (d) {
    if (
      typeof d[0] === 'object' &&
      d[0][0] == 'Paul' &&
      d[0][1] === 35 &&
      d[1][0] != undefined &&
      d[1][0] == 'dog' &&
      d[1][1] != undefined &&
      d[1][1] == 3
    ) {
      return true;
    } else {
      return false;
    }
  })(myArray)
);
```

# --solutions--


---
id: bad82fee1348bd9aedf08721
title: 使用 RGB 混合颜色
challengeType: 0
videoUrl: 'https://scrimba.com/c/cm24JU6'
forumTopicId: 18368
---

# --description--

就像使用十六进制编码一样，你可以通过不同值的组合，来混合得到不同的 RGB 颜色。

# --instructions--

将`style`标签里面中的十六进制编码替换为正确的 RGB 值。

<table class='table table-striped'><tbody><tr><th>Color</th><th>RGB</th></tr><tr><td>Blue</td><td><code>rgb(0, 0, 255)</code></td></tr><tr><td>Red</td><td><code>rgb(255, 0, 0)</code></td></tr><tr><td>Orchid</td><td><code>rgb(218, 112, 214)</code></td></tr><tr><td>Sienna</td><td><code>rgb(160, 82, 45)</code></td></tr></tbody></table>

# --hints--

文本内容为`I am red!`的`h1`元素的字体颜色应该为`red`。

```js
assert($('.red-text').css('color') === 'rgb(255, 0, 0)');
```

`red`颜色应使用`RGB`值。

```js
assert(
  code.match(
    /\.red-text\s*?{\s*?color:\s*?rgb\(\s*?255\s*?,\s*?0\s*?,\s*?0\s*?\)\s*?;\s*?}/gi
  )
);
```

文本内容为`I am orchid!`的`h1`元素的字体颜色应该为`orchid`。

```js
assert($('.orchid-text').css('color') === 'rgb(218, 112, 214)');
```

`orchid`颜色应使用`RGB`值。

```js
assert(
  code.match(
    /\.orchid-text\s*?{\s*?color:\s*?rgb\(\s*?218\s*?,\s*?112\s*?,\s*?214\s*?\)\s*?;\s*?}/gi
  )
);
```

文本内容为`I am blue!`的`h1`元素的字体颜色应该为`blue`。

```js
assert($('.blue-text').css('color') === 'rgb(0, 0, 255)');
```

`blue`颜色应使用`RGB`值。

```js
assert(
  code.match(
    /\.blue-text\s*?{\s*?color:\s*?rgb\(\s*?0\s*?,\s*?0\s*?,\s*?255\s*?\)\s*?;\s*?}/gi
  )
);
```

文本内容为`I am sienna!`的`h1`元素的字体颜色应该为`sienna`。

```js
assert($('.sienna-text').css('color') === 'rgb(160, 82, 45)');
```

`sienna`颜色应使用`RGB`值。

```js
assert(
  code.match(
    /\.sienna-text\s*?{\s*?color:\s*?rgb\(\s*?160\s*?,\s*?82\s*?,\s*?45\s*?\)\s*?;\s*?}/gi
  )
);
```

# --solutions--


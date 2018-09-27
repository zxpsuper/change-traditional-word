## Introduction

change-traditional-word 一键转化简繁体

## Usage

```
npm install change-traditional-word --save
```

支持es6 import, common.js, AMD 规范以及`<script>`标签引入

```js
import TraditionWord from 'change-traditional-word'
new TraditionWord()
```
or 
```js
const TraditionWord = require('change-traditional-word')
new TraditionWord()
```
or
```html
<script src="./traditional-word.js"></script>
<script>
  new TraditionalWord()
</script>
```

## Options
`new TraditionWord(bool, obj)`

bool

**type: String**

"true" --default(默认)

"false" -- 转化为简体

obj

**type: Object**

默认为 `document.body`，也可以自定义传入DOM元素

## Github

The above command pulls the template from [zxpsuper/change-traditional-word](https://github.com/zxpsuper/change-traditional-word), prompts for some information.

## Questions
If you have some questionn, you can send me a E-mail(zxpscau@163.com).
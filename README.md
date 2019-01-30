### pen
---
https://github.com/sofish/pen

```
bower install pen
```

```js
var editor = new Pen('#editor');
var editor = new Pen(document.getElementById('editor'));

var options = {
  editor: document.body,
  class: 'pen',
  debug: false,
  textarea: '<textarea name="content"></textarea>',
  list: ['bold', 'italic', 'underline'],
  linksInNewWindow: true
}
var editor = new Pen(options);

defaults = {
  class: 'pen',
  debug: false,
  textarea: '<textarea name="content"></textarea>',
  list: [
    'blockquote', 'h2', 'h3', 'p', 'insertorderedlist', 'insertunorderedlist',
    'indent', 'outdent', 'bold', 'italic', 'underline', 'createlink'
  ],
  stay: true,
  linksInNewWindow: false
}

options.title = {
  'blockquote': 'Blockquote'
  'createlink': 'Hyperlink'
  'insertimage': 'Image'
}

var pen = new Pen('#editor');
pen.destroy();

pen.rebuild();

var pen = new Pen('#editor');
pen.toMd();
```

```
<script src="src/pen.js"></script>
<script src="src/markdown.js"></script>
```



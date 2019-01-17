### Trumbowyg
---
https://github.com/Alex-D/Trumbowyg

```
npm install
npm install -g bower gulp
bower install
gulp build
```

```js
$('#thumbowyg-demo').trumbowyg();

$('#trumbowyg-demo').trumbowyg({
  btns: [['strong', 'em',],
  ['insertImage']],
    autogrow: true
});

$('#my-editor').trumbowyg();

$('textarea').thumbowyg({
  prefix: 'custom-prefix'
});

$('textarea').trumbowyg({
  lang: 'fr'
});

$('.editor-modern-ui').trumbowyg({
  prefix: 'modern-ui'
});

$.trumbowyg.svfPath = '/assets/my-custom-path/icons.svg';

$.trumbowyg.svgPath = false:

$('.editor').trumbowyg({
  svgPath: false
});

$('.a-disabled-editor').trumbowyg({
  disabled: true
});

$('.simple-editor').trumbowyg({
  btns: [['bold', 'italic'], ['link']]
});

$('.simple-editor').trumbowyg({
  btns: [
    ['viewHTML'],
    ['undo', 'redo'],
    ['formatting'],
    ['strong', 'em', 'del'],
    ['link'],
  ]
});

$.trumbowyg.hideButtonTexts = true

$('.trumbowyg').trumbowyg({
  hideButtonTexts: true
});

$('.trumbowyg').trumbowyg({
  sematic: false
});

$('.trumbowyg').trumbowyg({
  resetCss: true
});

$('.trumbowyg').trumbowyg({
  removeformatPasted: true
});

$('.trumbowyg').trumbowyg({
  tagsToRemove: ['script', 'link']
});

$('.trumbowyg').trumbowyg({
  tagsToKeep: ['i', 'script[src]']
});

$('.trumbowyg').trumbowyg({
  autogrow: true
});

$('.trumbowyg').trumbowyg({
  autogrowOnEnter: true
});

$('#editor')
.trumbowyg()
.on('tbwfocus', function(){
  console.log('Focus!'); });
.on('tbwblur', function(){
  console.log('Blur!'); });
```

```css
.trumbowyg-editor[contenteditable=true]:empty::before{
  content: attr(placeholder);
  color: #999;
}
```



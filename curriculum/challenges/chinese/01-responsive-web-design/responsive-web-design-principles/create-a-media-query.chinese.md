---
id: 587d78b0367417b2b2512b08
title: Create a Media Query
challengeType: 0
videoUrl: 'https://scrimba.com/c/cPp7VfD'
forumTopicId: 1
localeTitle: 创建一个媒体查询
---

## Description
<section id='description'>
媒体查询是 CSS3 中引入的一项新技术，它可以根据不同的可视窗口大小调整内容的布局。可视窗口是用户在网页上的可见区域，根据访问网站的设备不同而不同。
媒体查询由媒体类型组成，如果媒体类型与展示网页的设备类型匹配，则应用对应的样式。你可以在媒体查询中使用各种选择器和样式。
下面是一个媒体查询的例子，当设备宽度小于或等于 100px 时返回内容：
<code>@media (max-width: 100px) { /* CSS Rules */ }</code>
以下定义的媒体查询，是当设备高度大于或等于 350px 时返回内容：
<code>@media (min-height: 350px) { /* CSS Rules */ }</code>
只有当媒体类型与所使用的设备的类型匹配时，媒体查询中的 CSS 属性才生效。

</section>

## Instructions
<section id='instructions'>

增加一个媒体查询，当设备的高度小于或等于 800px 时，<code>p</code> 标签的 <code>font-size</code> 为 12px。
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: '当设备 <code>height</code> 小于或等于 800px 时，<code>p</code> 元素 <code>font-size</code> 应为 12px。'
    testString: assert($('p').css('font-size') == '12px', '当设备 <code>height</code> 小于或等于 800px 时，<code>p</code> 元素 <code>font-size</code> 应为 12px。');
  - text: '使用 <code>@media</code> 为 <code>height</code> 小于或等于 800px 的设备添加一个媒体查询。'
    testString: 'assert(code.match(/@media\s?\(max-height:\s*?800px\)/g), ''使用 <code>@media</code> 为 <code>height</code> 小于或等于 800px 的设备添加一个媒体查询。'');'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='html-seed'>

```html
<style>
  p {
    font-size: 20px;
  }
  
  /* Add media query below */
  
</style>
  
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus quis tempus massa. Aenean erat nisl, gravida vel vestibulum cursus, interdum sit amet lectus. Sed sit amet quam nibh. Suspendisse quis tincidunt nulla. In hac habitasse platea dictumst. Ut sit amet pretium nisl. Vivamus vel mi sem. Aenean sit amet consectetur sem. Suspendisse pretium, purus et gravida consequat, nunc ligula ultricies diam, at aliquet velit libero a dui.</p>
```



</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```

</section>
              
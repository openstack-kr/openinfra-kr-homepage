---
title: Styleguide
date: 2021-24-01
menu:
  footer_tertiary:
---

This is a paragraph — Markdown is a lightweight markup language that allows users to format plain text using a syntax that is easy to read and write. Created by John Gruber and Aaron Swartz, Markdown is widely used for formatting text on the web, such as in readme files, forums, and other online platforms. 

***

## Headings by default:

# H1 Default styles for headings
## H2 Default styles for headings
### H3 Default styles for headings
#### H4 Default styles for headings
##### H5 Default styles for headings
###### H6 Default styles for headings

***

## Lists

### Ordered list example:

1. Lightweight markup language
2. Simple and easy-to-read syntax
3. Commonly used for formatting text on the web
4. Utilizes symbols like asterisks, underscores, and hash symbols
5. Converts to HTML or other rich text formats

***

### Unordered list example:

* Fast and efficient static site generator
* Extensive theme and plugin support for customization
* Cross-platform compatibility
* Developed in the Go programming language
* Ideal for building and deploying static websites

***

## Table

##### Default Table using markdown syntax

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Content 1| Content 2| Content 3|
| Content 4| Content 5| Content 6|
| Content 7| Content 8| Content 9|

##### Table using table shortcode

{{< framework/table class="table table-striped table-bordered" >}}
| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Content 1| Content 2| Content 3|
| Content 4| Content 5| Content 6|
| Content 7| Content 8| Content 9|
{{</ framework/table >}}

## Quotes

##### Blockquote

> "Markdown, a language of simplicity and clarity, where the elegance of plain text meets the power to effortlessly transform ideas into beautifully formatted content with just a few keystrokes."

***

## Syntax Highlighter

```css
body {
  margin: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  width: 100vw;
  background-color: #1c2021;
}

li {
  width: 200px;
  min-height: 250px;
  border: 1px solid #000;
  display: inline-block;
  vertical-align: top;
  margin: 5px;
}
```

```js
  $('.top').click(function () {
    $('html, body').stop().animate({ scrollTop: 0 }, 'slow', 'swing');
  });
  $(window).scroll(function () {
    if ($(this).scrollTop() > $(window).height()) {
      $('.top').addClass("top-active");
    } else {
      $('.top').removeClass("top-active");
    };
  });
```

## Images

##### default markdown image

![Rom](/images/photos/content/content-4.webp)

##### figure shortcode

{{< framework/figure src="/images/photos/content/content-1.webp" title="Steve Francia"  caption="Designing in Figma" alt="Photo of designing a website in Figma" link="https://figma.com" target="_blank">}}

***

## Youtube Embed

{{< framework/youtube 2M6dJ2Uynhg >}}

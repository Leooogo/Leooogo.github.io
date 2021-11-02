---
layout: post
title: HTML and CSS
---

I'm planning to write some concept about frontend things.

Today's topic is some basic information about HTML and CSS.



Describe the role of HTML, CSS & JS in front-end development.
- HTML: content and structure
- CSS: style
- JS: dynamism and usability

What are the standard CSS selectors?
Standard CSS selectors are HTML tags, CSS classes or CSS ids.

What are the four types of CSS units?
Units can be absolute in px, relative to the parent element in %, relative to the viewport(window) height vh or width vw, or relative to the font size of the element in em.

What is a CSS class and why is it useful?
A CSS class is a HTML attribute used to define some re-usable CSS properties.

What is a CSS id and why is it useful?
A CSS id is an HTML attribute used to define some CSS properties for a unique element.

What are the three languages your browser speaks?
HTML, CSS & JavaScript

In the HTML skeleton, which markup contains metas and which one contains page content?
<head> markup contains metas which are read by the browser. <body> markup contains content which is displayed to the client by the browser.

✨✨✨✨✨
  The HTML head is the contents of the <head> element - unlike the contents of the <body> elememt(which are displayed on the page when loaded in a browser), the head's content is not displayed on the page. Instead, the head's job is to contain metadata about the document. In the above example, the head is quite small:
  <head>
    <meta charset="utf-8">
    <title>My test page</title>
  </head>
  In larger pages however, the head can get quite full.
✨✨✨✨✨

  
  
Why are the <title> & <meta name='description'> tags so important?
Both are basics for SEO, contents of those tags are read and displayed by Google in search results. So pay attention to write clear metas!
  
What is the box model?
Box model defines css dimension properties of a HTML element, a <div> basically. CSS properties width and height manage box content dimensions, padding manages space between content and box borders, margin manages space around the box and border manages box borders dimensions.

✨✨✨✨✨
  /* <length> values */
  width: 300px;
  width: 25em;

  /* <percentage> value */
  width: 75%;

  /* Keyword values */
  width: max-content;
  width: min-content;
  width: fit-content(20em);
  width: auto;

  /* Global values */
  width: inherit;
  width: initial;
  width: revert;
  width: unset;
  
  
  /* <length> values */
  height: 120px;
  height: 10em;

  /* <percentage> value */
  height: 75%;

  /* Keyword values */
  height: max-content;
  height: min-content;
  height: fit-content(20em);
  height: auto;

  /* Global values */
  height: inherit;
  height: initial;
  height: revert;
  height: unset;
  
  
  This property is a shorthand for the following CSS properties: padding-bottom, padding-left, padding-right, padding-top
  
  
  This property is a shorthand for the following CSS properties: margin-bottom, margin-left, margin-right, margin-top
  
  
  This property is a shorthand for the following CSS properties: border-color, border-style, border-width
✨✨✨✨✨


  

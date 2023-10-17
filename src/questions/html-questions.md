---
title: HTML Questions
layout: layouts/page.njk
permalink: /questions/html-questions/index.html
---

- What does a `doctype` do?
  > The `doctype` is used for two things, by different kinds of software: Web browsers use it to determine which rendering mode they should use. Markup validators look at the doctype to determine which rules they should check the document against.
- How do you serve a page with content in multiple languages?
  > To change the language, just simply set the lang attribute. We can define it anywhere in the document, such as in the body, in the paragraph, in the heading, or in the span tag. But the best practice is to set the lang in the span tag.\
  > `<p> French "<span lang="fr"> Bonjour </span>" </p>`\
  > `<p> Spanish "<span lang="es">Hola</span>" </p>`
- What kind of things must you be wary of when designing or developing for multilingual sites?
  > [Answer](https://www.greatfrontend.com/questions/quiz/designing-or-developing-for-multilingual-sites)
- What are `data-` attributes good for?
  > The data-\* attribute gives us the ability to embed custom data attributes on all HTML elements. The stored (custom) data can then be used in the page's JavaScript to create a more engaging user experience (without any Ajax calls or server-side database queries).
- Consider HTML5 as an open web platform. What are the building blocks of HTML5?
  > [Answer](https://www.greatfrontend.com/questions/quiz/html5-as-an-open-web-platform-building-blocks)
- Describe the difference between a `cookie`, `sessionStorage` and `localStorage`.
- Describe the difference between `<script>`, `<script async>` and `<script defer>`.
  > [Answer](https://medium.com/@yesseniapena219/describe-the-difference-between-script-script-async-and-script-defer-6fa91c3b4cc2)
- Why is it generally a good idea to position CSS `<link>`s between `<head></head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?
  > [Answer](https://www.greatfrontend.com/questions/quiz/css-link-between-head-and-js-script-just-before-body)
- What is progressive rendering?
- Why you would use a `srcset` attribute in an image tag? Explain the process the browser uses when evaluating the content of this attribute.
  > The srcset attribute in an image tag allows you to specify a list of different image resources and their size information. The browser can then choose the most appropriate image based on the device's resolution.\
  > For example, `<img srcset="small.jpg 500w, medium.jpg 1000w, large.jpg 2000w" src="..." alt="">` tells the browser to display the small, medium, or large .jpg graphic depending on the client's resolution. The first value is the image name and the second is the width of the image in pixels.
- Have you used different HTML templating languages before?
- What is the difference between `canvas` and `svg`?
  > Canvas and SVG are two different technologies for presenting content. Canvas is raster-based, meaning it uses arrays of pixels arranged on a grid. SVG is vector-based, meaning it uses mathematical metadata to describe a graphic.
- What are empty elements in HTML?
  > Examples of empty elements include:\
  > `<br>`: Defines a line break\
  > `<input>`: Receives input from the user\
  > `<meta>`: Specifies metadata about the page\
  > `<img>`: Inserts images into an HTML document\
  > You can check if an HTML element is empty using the “:empty” selector.\
  > HTML5 doesn't require empty elements to be closed.

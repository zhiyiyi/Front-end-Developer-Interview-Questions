---
title: CSS Questions
layout: layouts/page.njk
permalink: /questions/css-questions/index.html
---

- What is CSS selector specificity and how does it work?
  > CSS specificity is a set of rules that browsers use to determine which styles apply to an HTML element when multiple rules target the same element. Specificity is based on selectors' hierarchy and specificity values, which consist of four components: Inline styles, IDs, Classes/attributes, Elements.\
  > If there are two or more conflicting CSS rules that point to the same element, the browser follows some rules to determine which one is most specific and therefore wins out. The specificity algorithm is basically a three-column value of three categories or weights - ID, CLASS, and TYPE.\
  > The order of specificity rule which has precedence respectively is:\
  > Inline style\
  > Id Selector\
  > Inline styling, otherwise known as the “embedded stylesheet,” has the highest specificity and automatically takes precedence.
- What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
  > Normalizing maintains useful defaults over non-stylizing everything and it won't clutter your dev tools window. Moreover, Resetting is meant to strip all default browser styling on elements. For e.g. margins, paddings, font sizes of all elements are reset to be the same.
- Describe Floats and how they work.
  > Floats (elements where float isn't none).\
  > The float CSS property places an element on the left or right side of its container, allowing text and inline elements to wrap around it. The element is removed from the normal flow of the page, though still remaining a part of the flow (in contrast to absolute positioning).
- Describe z-index and how stacking context is formed.
  > [Answer](https://dev.to/anewman15/describe-z-index-and-how-stacking-context-is-formed-1oic#:~:text=A%20stacking%20context%20is%20a,contained%20within%20this%20stacking%20context.)
- Describe BFC (Block Formatting Context) and how it works.
- What are the various clearing techniques and which is appropriate for what context?
  > Empty div method: Uses an empty div with the style `clear:both;`\
  > Clearfix method: Refer to the `.clearfix` class above\
  > Overflow method: Sets the overflow CSS property on a parent element: `overflow: auto` or `overflow: hidden`\
  > Easy clearing method: Uses a CSS pseudo selector (`:after`) to clear floats\
  > The clear property can take the values of left, right, and both. Usually, you'll want to use both.\
  > The overflow method can be used in large projects. However, `overflow: hidden` might clip children if the children are taller than the parent.\
  > The `.clearfix` method is generally used in float layouts where elements are floated to be stacked horizontally.
- How would you approach fixing browser-specific styling issues?
  > [Answer](https://www.greatfrontend.com/questions/quiz/how-would-you-approach-fixing-browser-specific-styling-issues)
- How do you serve your pages for feature-constrained browsers?

  > Graceful degradation — The practice of building an application for modern browsers while ensuring it remains functional in older browsers.\
  > Progressive enhancement — The practice of building an application for a base level of user experience, but adding functional enhancements when a browser supports it.

- What techniques/processes do you use?
- What are the different ways to visually hide content (and make it available only for screen readers)?
  > [Answer](https://webaim.org/techniques/css/invisiblecontent/)
- Have you ever used a grid system, and if so, what do you prefer?
  > The float-based grid system, flex-based grid system.
- Have you used or implemented media queries or mobile specific layouts/CSS?

  > Media queries\
  >  Use a mobile-first approach\
  > Prioritize design and styles for smaller screens, such as smartphones, and then expand those styles to accommodate larger screens.\
  > Use media queries\
  > Media queries in CSS3 can be used to build iPhone-specific layouts for both portrait and landscape views.\
  > Use flexible layouts\
  > Use CSS properties like Flexbox and Grid to create a layout that doesn't look cluttered for the main screen sizes like mobile, tablet, and desktop.\
  > Here are some media query examples:\
  > Min-width\
  > 320px for smaller phone viewpoints, 480px for small devices and most phones, and 768px for most tablets\
  > Max-width\
  > 480px for smartphones, 767px for low resolution tablets and iPads, 1024px for tablets in portrait mode, and 1280px for desktops

- Are you familiar with styling SVG?
  > SVG has its own set of elements, attributes and properties to the extent that inline SVG code can get long and complex. By leveraging CSS and some of the forthcoming features of the SVG 2 specification, we can reduce that code for cleaner markup.
- Can you give an example of an `@media` property other than `screen`?
  > all: For all media type devices\
  > print: For printers\
  > speech: For screen readers that "reads" the page out loud\
  > screen: For computer screens, tablets, smart-phones, etc.
- What are some of the "gotchas" for writing efficient CSS?
- What are the advantages/disadvantages of using CSS preprocessors?
- Describe what you like and dislike about the CSS preprocessors you have used.
- How would you implement a web design comp that uses non-standard fonts?
  > Use the @font-face CSS rule\
  > Use font services like Google Webfonts and Typekit
- Explain how a browser determines what elements match a CSS selector.
  > For example with this selector p span, browsers firstly find all the <span> elements and traverse up its parent all the way up to the root to find the <p> element. For a particular <span>, as soon as it finds a <p>, it knows that the <span> matches and can stop its matching.
- Describe pseudo-elements and discuss what they are used for.
- Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.
- What does `* { box-sizing: border-box; }` do? What are its advantages?
- What is the CSS `display` property and can you give a few examples of its use?
- What's the difference between inline and inline-block?
- What's the difference between the "nth-of-type()" and "nth-child()" selectors?
- What's the difference between a relative, fixed, absolute and statically positioned element?
- What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
- Have you used CSS Grid?
- Can you explain the difference between coding a web site to be responsive versus using a mobile-first strategy?
- Have you ever worked with retina graphics? If so, when and what techniques did you use?
- Is there any reason you'd want to use `translate()` instead of _absolute positioning_, or vice-versa? And why?
- How is clearfix css property useful?
- Can you explain the difference between px, em and rem as they relate to font sizing?
- Can you give an example of a pseudo class? Can you provide an example use case for a pseudo class?
- What is the difference between a block level element and an inline element. Can you provide examples of each type of element?
- What is the difference between CSS Grid and Flexbox? When would you use one over the other?

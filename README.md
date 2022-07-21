# frontend-practice

[[course](https://www.udemy.com/course/design-and-develop-a-killer-website-with-html5-and-css3/?referralCode=93317126211B2A500938)] - [[repo](https://github.com/jonasschmedtmann/html-css-course)] - [[discord](https://discord.gg/uhMkpf4)]

## resource

[[Jonas' resources for hand-crafting
beautiful and performant websites](http://codingheroes.io/resources/)]

## HTML

**[Semantic HTML](https://www.w3schools.com/html/html5_semantic_elements.asp):** We should not think about what the HTML element look like as it is rendered on the page. But instead, we should think about _what the element actually mean?_, _what it stand for?_. When we markup the content with specific HTML element, we assign the meaning to it. [Let's Talk about Semantics](https://html5doctor.com/lets-talk-about-semantics/)

## CSS

[CSS Naming Conventions](https://www.freecodecamp.org/news/css-naming-conventions-that-will-save-you-hours-of-debugging-35cea737d849/)

[BEM](https://css-tricks.com/bem-101/) - [home page](https://en.bem.info/) - [side effect in CSS](http://philipwalton.com/articles/side-effects-in-css/) - [chaining BEM modifier](http://webuild.envato.com/blog/chainable-bem-modifiers/) - [BEM principles](http://www.smashingmagazine.com/2012/04/16/a-new-front-end-methodology-bem/) - [transparent with namespace](https://csswizardry.com/2015/03/more-transparent-ui-code-with-namespaces/)

[Selectors](https://www.w3.org/TR/selectors-3/#selector)

[CSS Cascade Layers](https://css-tricks.com/css-cascade-layers/) - [Cascade and inheritance](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Cascade_and_inheritance)

[Specificity](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity) - [more](https://css-tricks.com/specifics-on-css-specificity/) - [Calculating a selector specificity](https://www.w3.org/TR/selectors-3/#specificity)

Box Model: [basic](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model) - [detail](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model) - [box-sizing](https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing)

## CSS Tips & Notes

1. **Margin:** use it specify a space between elements. When we want to specify vertical space, try to stick with `margin-bottom` only.
2. **Centering the page:** first, specify width of the page `width: {size}px;`. Then use `margin: 0px auto;`. The browser will auto compute the margin left & right for you.
3. **Inline Elements:** occupies necessary space for its content. Causes no _line-break_ after or before the element. `height` and `width` do not apply. `padding` and `margin` are only applied horizontally (left and right).
4. **Inline Block:** Looks like inline from the **outside**, behaves like block level on the **inside**.
5. **Absolute Position:** base on the **first parent element** which has been specified `position: relative;`

## Tools

[Specificity Calculator](https://specificity.keegan.st/)

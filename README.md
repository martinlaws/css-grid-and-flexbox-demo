# CSS Grid Layout Demo
by [Martin Laws](https://twitter.com/martinblaws), Front End @ [Ample Organics](http://www.ampleorganics.com)

---

### What's the difference between Flexbox and CSS Grid?
Flexbox is one-dimensional. Each row becomes its own `flex-container`, meaning that members of a row only know about their direct siblings, they are _not aware of members of other flex-containers_. This is not a problem when the layout is one-dimensional (e.g. top -> bottom, left -> right), but becomes highly problematic when you want vertical and horizontal layout control.
![Flexbox Layout Example](https://i.imgur.com/cLRrezS.png)

Grid allows you to declare two-dimensional layouts, much in the same way as third-party grids (Bootstrap, Foundation, Skeleton, etc.), but is _native to CSS_.
![Grid Layout Example](https://i.imgur.com/OTN63a5.png)

### Links and Reference Material
* [CSS Grid Docs (MDN)](https://developer.mozilla.org/en-US/docs/Glossary/Grid)
* [Flexbox Docs (MDN)](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout)
* [Box Module Docs (W3)](https://www.w3.org/TR/css-align-3/#intro)
* [Feature/`@supports` Query Docs (MDN)](https://developer.mozilla.org/en-US/docs/Web/CSS/%40supports)

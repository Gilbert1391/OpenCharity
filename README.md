# Open Charity Template

A template for Drupal theming built from scratch using HTML and CSS, no framework.

## Solution

I took a look at the design and broke it down into different reusable components. Below I list the main features I used to build this site.

## Flexbox

Flexbox is supported in all major browsers and it's very easy to use. Flexbox simplifies complexity, it allows us to achieve complex layouts with a few lines of code.

## SASS

The main reason I use a CSS pre-processor like SASS is because I tend to work with components, it's way easier for me to reuse components from different projects using SASS instead of just plain CSS, it's quite useful to keep the code DRY and organized. There are other great benefits, such as the use of variables (for colors, margins, etc) and mixins (media queries). Also, as the project grows and becomes more complex, so will the stylesheets. Fortunately SASS has the `@import` rule. `@import` allows you to modularize your code making it easier to maintain by importing smaller SASS files.

## BEM

I use the Block, Element, Modifier methodology for modularity purposes, it reduces style conflicts by keeping CSS specificity to a minimum level. Plus BEM gives everyone on a project a declarative syntax that they can share so that they're on the same page.

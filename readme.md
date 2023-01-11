# Clipboard Website Tailwind Project
Deployed on Netlify on the following link [Clipboard Website](https://frabjous-marzipan-4591ce.netlify.app/ "Link to page")

## What have I learned making this project?
+ How to change SVGs fill color.
```css
fill="#4C545C" fill-rule="nonzero"
```
+ How to apply Tailwind directives to base layer and custom styles.
+ How important it is to use semantic HTML and add comments to HTML code when using Tailwind, e.g.
```html
<!-- Menus -->
 <div
   class="flex flex-col space-y-4 md:flex-row md:ml-24 md:space-x-24 md:space-y-0"
  >
 <!-- Menu 1 -->
 <div class="flex flex-col space-y-4 text-center md:text-left">
```
+ How to reduce the amount of Tailwind classes using custom classes (and where to place them).
+ How to deploy on Netlify.
+ Got acquainted with some of the features offered by Netlify.
+ How to extend the tailwind.config to include custom fonts and colors, e.g.
```javascript
extend: {
      screens: {
        sm: "480px",
        md: '768px',
        lg: '976px',
        xl: '1440px'
      },
        colors: {
          strongCyan: 'hsl(171, 66%, 44%)',
          lightBlue: 'hsl(233, 100%, 69%)',
          darkGrayishBlue: 'hsl(210, 10%, 33%)',
          grayishBlue: 'hsl(201, 11%, 66%)'
        },
        fontFamily: {
          sans: ['Bai Jamjuree', 'sans-serif']
        }
    },
 ```

## What was the most difficult part of this project?
Nothing was particularly difficult, but If I had to single out something, it would probably be keeping track of all the flex elements (because all the items on the page are spread out in such a way that flex is the perfect approach and therefore had to be used often). 

____
| Project enjoyment | Project educational value | Total score | 
|-------------------| --------------------------|-------------|
| 4/5               |  3/5                      | 3.5/5

# steel-grid

A simple and easy to use grid system built with CSS for layouts.

Built with width's from 1-24 columns.

[Link to grid example:](https://dannypaton.github.io/steel-grid) 


## Installation

```js
npm install steel-grid
```
Download or clone this repo, then include `steel-grid.css` or `steel-grid.min.css` in your working folder and point to the CSS path in your HTML:

`<link rel="stylesheet" href="./steel-grid.css">` 
or
`<link rel="stylesheet" href="./steel-grid.min.css">`

## Quick Start

This is how you implement the HTML by using one to three custom attributes.
`d-grid=""` (desktop size)
`t-grid=""` (tablet size)
`m-grid=""` (mobile size)

|CSS Attribute | CSS value|
|-------------------|------|
|`d-grid`: *number* | 1-24|
|`t-grid`: *number* | 1-24|
|`m-grid`: *number* | 1-24|

Place a number between 1-24 as the value of each attribute which will equal the column's width.

HTML must be build in a similar way as the example below. 

Start each section, place a div inside of it with a class of row, then build with the grid system inside that.

**Example**:

```html
<section>
        <div class="row">
            <div d-grid="12" t-grid="12" m-grid="24">
            </div>
            <div d-grid="12" t-grid="12" m-grid="24">
            </div>
        </div>
</section>
```

### Other Notes

Included is an example folder which shows the possibilities and different uses of the Steel Grid system! Open it in your editor to see how it works.

Each number takes up a certain % of space on the page per column.

**Further Explanation:**

If you have 1 div with `d-grid="24"` it will take up the whole page's width.

If you have 2 divs with `d-grid="12"` they will each take up half the page's width.

If you have 3 divs with `d-grid="8"` they will each take up a third of the page's width.

You can also insert a blank column to put space in between your content easily by using a div to take up as many column's of space that you'd like depending on the number:

`<div desktop-grid="1"></div>`

### Author

Built by Danny Paton
# bootstrap-silicium
 
## Bootstarp is a CSS responsive framework

---

**To use bootstrap , we should have add bootstrap css and bootstrap js to our webpage (we can link to cnd files or local files) Like :**
```
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">
  </head>
  <body>
    <h1>Hello, world!</h1>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2" crossorigin="anonymous"></script>
  </body>
</html>
```

*After add bootstrap to our web page , we can use classes that defined in bootstrap . like*

```
<h1 class="display-1">
    Bootstrap course
</h1>
```

> See directory 1>index.html for more info.

---

**For rtl websites we should use bootstrap rtl, **

```
<!doctype html>
<html lang="fa" dir="rtl">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.rtl.min.css" integrity="sha384-dc2NSrAXbAkjrdm9IYrX10fQq9SDG6Vjz7nQVKdKcJl3pC+k37e7qJR5MVSCS+wR" crossorigin="anonymous">
    <title>درس بوتسترپ</title>
  </head>
  <body>
    <h1>سلام دنیا</h1>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2" crossorigin="anonymous"></script>
  </body>
</html>

```

> See directory 2>index.html for more info.

---

**Bootstrap have multiple colors for background**
+ For more information about these background , use this [Link](https://getbootstrap.com/docs/5.2/utilities/background/)

*Main topics are :*
1. Background Color
2. Gradiant Background Color
3. Opacity Background Color

> See directory 3>index.html for more info.

---

**Bootstrap have multiple colors for texts**
+ For more information about these colors , use this [Link](https://getbootstrap.com/docs/5.2/utilities/colors/)

*Main topics are :*
1. Text Colors
2. Opacity

> See directory 4>index.html for more info.

---

**Bootstrap have classes for borders**
+ For more information about these borders , use this [Link](https://getbootstrap.com/docs/5.2/utilities/borders/)

*Main topics are :*
1. Borders Additive
2. Borders Subtractive
3. Borders Colors
4. Borders Width
5. Border Radius
6. Border Radius Sizes

> See directory 5>index.html for more info.

---

**To change display of element , we can use d-{display_type} Like**
+ For more information about these colors , use this [Link](https://getbootstrap.com/docs/5.2/utilities/display/)


**Also we can also use breakpoints to hide or unhide the elements**
+ For more information about these breakpoints , use this [Link](https://getbootstrap.com/docs/5.2/layout/breakpoints/)

> See directory 6>index.html for more info.

---

**We can float our elements in bootstrap with float property**
+ For more information about float , use this [Link](https://getbootstrap.com/docs/5.2/utilities/float/)

*Main topics are :*
1. float types
2. float types with break-point

> See directory 7>index.html for more info. 

---

**We can check user interaction**
+ For more information about interactions , use this [Link](https://getbootstrap.com/docs/5.2/utilities/interactions/)

*Main topics are :*
* text types :*
1. Text selection
2. Pointer events

> See directory 8>index.html for more info.

---

**We can opacity background with Opacity classes like bg-opacity-{value} or opacity element with opacity-{value} Like :**

*Main topics are :*
1. bg-opacity-{values}
2. opacity-{value}

+ For more information about opacity , use this [Link](https://getbootstrap.com/docs/5.2/utilities/opacity/)


> See directory 9>index.html for more info.

---

**We can use overflow property to add action when overflow happened . Overflow types are :**

+ For more information about overflow , use this [Link](https://getbootstrap.com/docs/5.2/utilities/overflow/)

*Main topics are :*
1. overflow-{type}

*Diffrence detween overflow-auto and overflow-scroll if overflow-scroll allows us to have scroll in width and height but overflow-auto just scrolls in height .*

> See directory 10>index.html for more info.

---

**We can justify position with position-{position_type} and with top-{value} , bottom-{value} , right-{value} and left-{value} , we can set position of element .**
+ For more information about positions , use this [Link](https://getbootstrap.com/docs/5.2/utilities/position/)

*Also we can set elements middle by tranlate-middle or tranlate-middle-x or tranlate-middle-y (tranlate-middle means tranlateX(-50%) and tranlateY(-50%))*


*Main topics are :*
1. position-{type}
2. translate-middle

> See directory 11>index.html for more info and examples.

---

**We can add shadow to our elements with shadow-{shadow-type} .**

+ For more information about shoadows , use this [Link](https://getbootstrap.com/docs/5.2/utilities/shadows/)

*Main topics are :*
1. shadow-{weight of shadow}

> See directory 12>index.html for more info and examples.

---

**With sizing we can set width and height of the element . _But its better to use flex and grid !!!_**

+ For more information about sizing , use this [Link](https://getbootstrap.com/docs/5.2/utilities/sizing/)

*Main topics are :*
1. w-{value}
2. h-{value}
3. mh-{value}
4. mw-{value}

> See directory 13>index.html for more info and examples.

---

**We can multiple class for set text properties.**
+ For more information about text , use this [Link](https://getbootstrap.com/docs/5.2/utilities/text/)

*Main topics are :*
1. Text alignment with text-{align}
2. Text wrapping with text-{wrap or nowrap}
3. Word break with text-break
4. Text transform with text-{type of transform}
5. Font size with fs-{size}
6. Font weight with fw-{weight}
7. Font style with fst-{style}
8. Line height with lh-{type or value}
9. font-monospace
10. Reset color (inherits parent) with text-reset
11. Text decoration with text-decoration-{type}

> See directory 14>index.html for more info and examples.

---

**With align property , we can set align of text**

+ For more information about vertical align , use this [Link](https://getbootstrap.com/docs/5.2/utilities/vertical-align/)


*Main topics are :*
1. align-{type}
2. align-text-{type}

> See directory 15>index.html for more info and examples.

---

**We can vibible or invisible elements in bootstrap**
+ For more information about visibility , use this [Link](https://getbootstrap.com/docs/5.2/utilities/visibility/)


*Main topics are :*
1. visibility

**Diffrence between d-none (display none) and invisible is d-none there is no footprint that element exist but invisibe just invisibe item**


> See directory 16>index.html for more info and examples.
---

**We can use clearfix to clear floated content**
+ For more information about clearfix , use this [Link](https://getbootstrap.com/docs/5.2/helpers/clearfix/)


*Main topics are :*
1. clearfix

> See directory 17>index.html for more info and examples.

---

**There are pre-defined color-backgroundcolor in bootstrap**
+ For more information about color-backgroundcolor , use this [Link](https://getbootstrap.com/docs/5.2/helpers/color-background/)


*Main topics are :*
1. text-bg-{color}

**Note : These classes change color and background color with together !**

> See directory 18>index.html for more info and examples.

---

**There are pre-defined link colors in bootstrap**
+ For more information about link colors , use this [Link](https://getbootstrap.com/docs/5.2/helpers/colored-links/)


*Main topics are :*
1. link-{color}

> See directory 19>index.html for more info and examples.

---

**We can set position fixed or sticky for elements**
+ For more information about these positions , use this [Link](https://getbootstrap.com/docs/5.2/helpers/position/)

*Main topics are :*
1. {fixed or sticky}-{top or bottom}
2. {fixed or sticky}-{breakpoint type}-{top or bottom}

> See directory 20>index1.html & index2.html for more info and examples.

---

**We can apply flex quickly in bootstrap , we can use hstack and vstack classes**
+ For more information about these stacks , use this [Link](https://getbootstrap.com/docs/5.2/helpers/stacks/)

**We can use gap-{value} to space between elements**
+ For more information about gap , use this [Link](https://getbootstrap.com/docs/5.2/utilities/spacing/#gap)

**We can use vertical rule with vr class easily.**
+ For more information about vr , use this [Link](https://getbootstrap.com/docs/5.2/helpers/vertical-rule/)

*Main topics are :*
1. vstack and hstack
2. gap-{value}
3. vr

> See directory 21>index.html for more info and examples.

---

**We can use text-truncate class to truncate words**
+ For more information about these stacks , use this [Link](https://getbootstrap.com/docs/5.2/helpers/text-truncation/)

*Main topics are :*
1. text-truncate

> See directory 22>index.html for more info and examples.

---

**Bootstrap predefined styles for each element and named it Reboot**
+ For more information about these reboots , use this [Link](https://getbootstrap.com/docs/5.2/content/reboot/)

---

**Bootstrap predefined styles for Typography**
+ For more information about typography , use this [Link](https://getbootstrap.com/docs/5.2/content/typography/)

*Main topics are :*
1. h{value}
2. display-{value}
3. lead -> better for first paragraph
4. class mark , small , text-docoration-underline , text-decoration-line-through like this tags and attributes
5. initialism for abbr tags
6. blockquote & blockquote-footer for Blockquotes 
7. list styles with list-unstyled and list-inline & list-inline-items

---
**Bootstrap have classes for Images**
+ For more information about typography , use this [Link](https://getbootstrap.com/docs/5.2/content/images/)

*Main topics are :*
1. img-fluid to create responsive image
2. img-thumbnail to give rounded 1px border
3. images alignment

---

**Bootstrap have classes for Tables**
+ For more information about typography , use this [Link](https://getbootstrap.com/docs/5.2/content/tables/)

*Main topics are :*
1. table class for table tag
2. table color with table-{color}
3. table-striped and table-striped-columns
4. table-hover
5. table-active
6. table-bordered and table-borderless
7. table-group-divider

---

**Bootstrap have classes for Figures (image with caption)**
+ For more information about typography , use this [Link](https://getbootstrap.com/docs/5.2/content/figures/)

*Main topics are :*
1. figure
2. figure-caption

---

**Bootstrap use container classes for padding inner elements**

*Main topics are :*
1. container
2. container-{size}
3. container-fluid

> See directory 23>index.html for more info and examples.

---

**Bootstrap have grid system and apply 12 column for element**
+ For more information about grid system , use this [Link](https://getbootstrap.com/docs/5.2/layout/grid/)

*Main topics are :*
1. row
2. col
3. col-{value}
4. col-{size}-{value}

**We can also set space between elements with gutter**
+ For more information about gutter , use this [Link](https://getbootstrap.com/docs/5.2/layout/gutters/)

*Main topics are :*
1. g-{value}
2. gx-{value}
3. gy-{value}

> See directory 24>index.html for more info and examples.

---

**With justify-content we can set position element in width in grid system and flexbox**
+ For more information about gutter , use this [Link](https://getbootstrap.com/docs/5.2/layout/columns/#horizontal-alignment)

*Main topics are :*
1. justify-content-{type}

> See directory 25>index.html for more info and examples.

---

**With align-items we can set position element in height in grid system and flexbox**
+ For more information about gutter , use this [Link](https://getbootstrap.com/docs/5.2/layout/columns/#vertical-alignment)

*Main topics are :*
1. align-items-{type}
1. align-self-{type}

> See directory 26>index.html for more info and examples.

---

**Grid system uses flex box but there is a extra properties that allows us use grid system with css grid . But its better not to use css grid because many platforms not support them**
+ For more information about gutter , use this [Link](https://getbootstrap.com/docs/5.2/layout/css-grid/)

---

**Remaining topics:**
+ Margin
  1. m-{value}
  2. mx-{value}
  3. my-{value}
  4. ms-{value}
  5. me-{value}
  6. mt-{value}
  7. mb-{value}
+ Padding
  1. p-{value}
  2. px-{value}
  3. py-{value}
  4. ps-{value}
  5. pe-{value}
  6. pt-{value}
  7. pb-{value}

---

**Components and Forms in bootstrap can use in project when the needs**

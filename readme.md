# HTML/CSS Review

This is a review of your working knowledge of HTML and CSS. Note that this review is designed to help you recall and familiarize yourself with technical concepts.

## Getting Started

* Fork and clone this repository
* Answer the following questions by...
  * Opening this file in Sublime
  * Answering the questions via Markdown. Feel free to refer to this [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Commit your changes
* Make a pull request for submission

---

## HTML

1.) Create a valid, empty HTML page with the necessary tags.

```html
<!DOCTYPE html>
<html>
  <head>
    <title></title>
  </head>
  <body></body>
</html>
```

2.) What are the differences between these tags?

```html
<!-- Tag 1 -->
<img src="images/me.jpg" alt="My profile image">

<!-- Tag 2 -->
<div></div>
```

```
IMG is a self-closing tag, div requires and opening and closing tag
```

---

## CSS

1.) Compare and contrast the following ways to add CSS to HTML elements.

```html
<!-- Inline CSS -->
<div style="background-color: red;"></div>

<!-- Internal style sheet -->
<style type="text/css">
  div {
    background-color: red;
  }
</style>

<!-- External style sheet (not shown) -->
<link rel="stylesheet" type="text/css" href="css/style.css">
```

```
first applies only within the tag, the second affects all divs only on that page, the third is for all pages that link to that css file. The order of which rule is applied is CSS Page -> Style Tags with page -> Style markup within div. 
```

2.) Below are some different CSS selectors. Use CSS comments to describe what each selector will do.

```css
/* This div will display as a circle */
div {
  border-radius: 50%;
}

/*the P tags will display text that's 18xp high */
.header p {
  font-size: 18px;
}

/* this sets the footer to be always at the bottom of the screen */
.footer {
  position: absolute;
  bottom: 0;
}


/* this resizes the image fill the browser screen */
.splash-image {
  background-image: url("../images/ocean.jpg");
  background-size: cover;
  width: 100%;
}

/* When the element is hovered, it will disappear from the page */

.ninja:hover {
  display: none;
  color: black;
}
```


---

## Licensing
1. All content is licensed under a CC-BY-NC-SA 4.0 license.
2. All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.

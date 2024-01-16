# Fun with CSS

## Table of Contents

0. [Sprite Languages](#sprite-languages)
1. [Move the (Under)line](#move-the-underline)
2. [Toggle](#toggle)
3. [Menu](#menu)

---

## 0. Sprite Languages

### Instructions

By using the provided HTML and image file, create a CSS layout as shown below:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 0- Sprite</title>
        <link href="0-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <ul>
            <li>HTML<span class="icon i-html"></span></li>
            <li>CSS<span class="icon i-css"></span></li>
            <li>JavaScript<span class="icon i-js"></span></li>
        </ul>
    </body>
</html>
```
**generate this layout:**

![html-css-js](/hcj.png)

### Layout

You are not allowed to change the image and the HTML - sprite is cool!

---

## 1. Move the (Under)line

### Instructions

By using the provided HTML, create a CSS layout where the underline is hidden by default and appears slowly:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 1- Underline</title>
        <link href="1-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <h2>
            Hello <a href="https://www.holbertonschool.com">Holberton!</a>
        </h2>
    </body>
</html>
```
**generate this layout:**

![holb](/holb.gif)

### Layout

You are not allowed to change the HTML.

---

## 2. Toggle

### Instructions

By using the provided HTML, create a CSS layout where the `<input>` has a custom toggle design:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>
        <link href="2-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <div class="toggle">
            <input type="checkbox" name="toggle" class="toggle-cb" id="toggle-0" checked>
            <label class="toggle-label" for="toggle-0">
                <div class="toggle-inner"></div>
                <div class="toggle-switch"></div>
            </label>
        </div>
    </body>
</html>
```

generate this layout:
**Checked:**

![checked](/checked.png)

**Unchecked:**

![unchecked](/unchecked.png)

### Layout

You are not allowed to change the HTML.

---

## 3. Menu

### Instructions

By using the provided HTML, create a CSS layout/animation for the menu:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 3- Menu</title>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
        <link href="3-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <nav class="menu">
            <input type="checkbox" href="#" class="menu-open" name="menu-open" id="menu-open"/>
            <label class="menu-open-button" for="menu-open">
                <span class="menu-line menu-line-1"></span>
                <span class="menu-line menu-line-2"></span>
                <span class="menu-line menu-line-3"></span>
            </label>
            <a href="#" class="menu-item"> <i class="fa fa-area-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-bar-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-line-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-pie-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-table"></i> </a>
        </nav>
    </body>
</html>
```

**generate this layout:**

![hamb](/menu.gif)

### Layout/Animation

You are not allowed to change the HTML.

---
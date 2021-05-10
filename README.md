<h1 style="text-align: center;">Horiseon Social Solution Services</h1>

[[Deployed-Site]](https://jdogcrane.github.io/work1/)

[[Site-Preview]](#Site-Preview)

## General overview: 
 ```
 Code has been refactored and search engine optimized. Streamlined and simplified into a logical structure with better semantics. Webpage meets accessibility standards. When you view the source code you will find semantic HTML elements. Elements follow a logical structure independent of styling and positioning. Alt attributes are now present. Heading attributes fall in sequential order. The title element has a concise and descriptive title. 
 ```

## Table of Contents:

HTML Changes
- [Head](#Head)
- [Header](#Head)
- [Body](#Body)
- [Main](#Main)
- [Section](#Section)
- [Aside](#Aside)
- [Footer](#Footer)

CSS Changes
- [CSSHeader](#CSSHeader)
- [CSSBody](#CSSBody)
- [CSSMain](#CSSMain)
- [CSSSection](#CSSSection)
- [CSSAside](#CSSAside)
- [CSSFooter](#CSSFooter)

---
<h3 style="text-align:center;">HTML-Changes</h3>

---
### Head:
* Renamed title to represent the page more accurately.

### Header:
* Replaced div with `<header>` for semantics
* Changed `<div>` into `<nav>` for semantics
* Removed `<li>` elements and simplified their function into `<a>`
* Fixed Search Engine Optimization anchor Link
* Changed `<span>` into `<abbr>` for semantics
* Added `a:hover` for better functionality

### Body:
* Changed `<div>` into `<img>` to represent class more specifically

### Main:
* Replaced `<div>` with `<main>` for semantics

### Section:
* Changed `<div>` into `<section>` for semantics
* Nested attributes into `<img>` like id & class for simplicity
* Added alt text to `<img>`'s

### Aside:
* Changed `<div>` into `<aside>` for semantics
* Removed unnecessary `<div>` and nested class into `<aside>` for simplicity
* Added alt text to `<img>`'s

### Footer:
* Changed `<div>` into `<footer>` for semantics
* Changed `<h2>` into `<h4>` for numerical order and semantics
---
<h3 style="text-align:center;">CSS-Changes</h3>

---
### CSSHeader:
* Changed `.header` into `<header>` for semantics
* Changed `.header h1` into `h1` for semantics
* Changed `.header h1 .seo` into `h1 .seo` for semantics
* Changed `.header div` into `<nav>` for semantics
* Removed `.header div ul` to remove redundancy for simplicity
* Added padding to `<a>` to replace unnecessary `<li>` used as padding

### CSSBody:
* Moved `Body` under `<header>` in css to keep things orderly
* Renamed `.hero` to `backdrop-img` for better description of class

### CSSMain:
* Changed `.content` into `<main>` for semantics
* Moved `main` under `body` in css to keep things orderly

### CSSAside:
* Changed `.benefits` into `<aside>` for semantics
* Changed & grouped redundant `.benefit-brand h3`, `.benefit-cost h3`, `.benefit-lead h3` into `<h3>` for simplicity
* Grouped redundant `.benefit-lead`, `.benefit-brand`, `.benefit-cost` into `benefit-brand` for simplicity
* Grouped redundant `.benefit-lead img`, `.benefit-brand img`, `.benefit-cost img` into `.benefit-brand img` for simplicity
* Grouped redundant `.online-reputation-management`, `.social-media-marketing`, `.search-engine-optimization` into `.social` 
* Grouped redundant `.online-reputation-management img`, `.social-media-marketing img`, `.search-engine-optimization img` into `.social img` for simplicity
* Changed & grouped redundant `.search-engine-optimization h2`, `.online-reputation-management h2`, `.social-media-marketing h2` into `<h2>` for semantics

### CSSFooter:
* Changed `.footer` into `footer` for semantics
* Changed `.footer h2` into `footer h4` for semantics & numerical order on html
* Removed unnecessary class targeting text in aside/footer

### CSSOptimization:

* Added `img { image-rendering: optimizeSpeed; image-resolution: 72dpi; }` in attempt to help images load quicker
>Note: During class on monday 5/10/21 anthony went over resizing, so I did that as well.

# Site Preview
![image_url](https://cdn.discordapp.com/attachments/709148993262977068/841119274961207306/mysite.jpg "Site preview")
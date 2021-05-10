<h2 style="text-align: center;">Change Log</h2>
>Site Link: https://jdogcrane.github.io/work1/
### General overview: 
 Code has been refactored and search engine optimized. Streamlined and simplified into a logical structure with better semantics.

---
<h3 style="text-align:center;">HTML-Changes</h3>

---
### Head:
* Renamed title to represent the page more accurately.

### Header:
* Replaced div with `<header>` for semantics
* Changed `<div>` into `<nav>` for semantics
* Removed `<li>` elements and simplified their function into `<a>`
* Fixed Search Engine Optimization Hyper Link

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
### Header:
* Changed `.header` into `<header>` for semantics
* Changed `.header h1` into `h1` for semantics
* Changed `.header h1 .seo` into `h1 .seo` for semantics
* Changed `.header div` into `<nav>` for semantics
* Removed `.header div ul` to remove redundancy for simplicity
* Added padding to `<a>` to replace unnecessary `<li>` used as padding

### Body:
* Moved `Body` under `<header>` in css to keep things orderly
* Renamed `.hero` to `backdrop-img` for better description of class

### Main:
* Changed `.content` into `<main>` for semantics
* Moved `main` under `body` in css to keep things orderly

### Aside:
* Changed `.benefits` into `<aside>` for semantics
* Changed & grouped redundant `.benefit-brand h3`, `.benefit-cost h3`, `.benefit-lead h3` into `<h3>` for simplicity
* Grouped redundant `.benefit-lead`, `.benefit-brand`, `.benefit-cost` into `benefit-brand` for simplicity
* Grouped redundant `.benefit-lead img`, `.benefit-brand img`, `.benefit-cost img` into `.benefit-brand img` for simplicity
* Grouped redundant `.online-reputation-management`, `.social-media-marketing`, `.search-engine-optimization` into `.social` 
* Grouped redundant `.online-reputation-management img`, `.social-media-marketing img`, `.search-engine-optimization img` into `.social img` for simplicity
* Changed & grouped redundant `.search-engine-optimization h2`, `.online-reputation-management h2`, `.social-media-marketing h2` into `<h2>` for semantics

### Footer:
* Changed `.footer` into `footer` for semantics
* Changed `.footer h2` into `footer h2` for semantics & numerical order on html
* Removed unnecessary class targeting text in aside/footer

### Optimization:

* Added `img { image-rendering: optimizeSpeed; image-resolution: 72dpi; }` in attempt to help images load quicker
>Note: Did not find a way to optimize images very well without modifying the image file. I don't think im allowed to do that so I made no attempt using third-party applications on the images to reduce file size.

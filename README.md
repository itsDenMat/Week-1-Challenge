# HTML, CSS, and Git: Code Refactor (Module 1 Challenge)

Refactoring existing code to meet a certain set of standards and to optimized the website to have accesibility standards.

## Tasks Done

* Title element is fixed to have concise and descriptive title.
* Source codes uses semantic HTML elements.
* Logical structure in source code is implemented for easy viewing.
* Alt attributes are utilized to provide descriptions to icons and images.
* Heading attributes are placed in sequential order.
<br />

## Before and After Changes

### Title Element
Original title element was not descriptive of the webpage with a vague title of "website". Provided with a short but concise description of the current title of the webpage by putting "Horiseo Homepage".
* Original
    ```
    <title>website</title>
    ```
* Implemented code
  ```
  <title>Horiseo Homepage</title>
  ```
<br />

### Using semantic HTML elements 
Certain div elements were replaced with semantic HTML elements to provide more structure of understanding each parts of the codes.


>__HEADER__
* Original
  ```
  <div class="header">
  ```
* Implemented code
  ```
  <header class="header">
  ```

>__MAIN__
* Original
  ```
  <div class="content">
  ```
* Implemented code
  ```
  <main class="content">
  ```
>__benefits SECTION__
* Original
  ```
  <div class="benefits">
  ```
* Implemented code
  ```
  <section class="benefits">
  ```
>__FOOTER__
* Original
  ```
  <div class="footer">
  ```
* Implemented code
  ```
  <footer class="footer">
  ```
<br />

### Logical Structure
All line of codes are indented properly for better viewing of code lines and nesting.

```
<header class="header">
    <h1>Hori<span class="seo">seo</span></h1>
    <section>
        <ul>
            <li>
                <a href="#search-engine-optimization">Search Engine Optimization</a>
            </li>
            <li>
                < a href="#online-reputation-management">Online Reputation Management</a>
            </li>
            <li>
                <a href="#social-media-marketing">Social Media Marketing</a>
            </li>
        </ul>
    </section>
</header>
```
<br />

### ALT Attributes
Alt attributes were placed to provide description when icons and images used doesn't load.

<br />

### Sequential Order of Heading Attributes
Heading attributes were made sure that it were in sequential order to provide better well structured headings. Sequential order were from H1 down to H4.

<br />

### Final Look of the Web Page
The following image shows the final appearance
![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](desktop/../assets/images/01-html-css-git-homework-demo.png)

<p align="center">
Click the link below to access work:
</p>

<p align="center">
<a href="#">Horiseon Webpage</a>
</p>

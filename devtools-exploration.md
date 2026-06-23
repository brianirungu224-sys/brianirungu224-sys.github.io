# Task 1.2: DevTools Exploration

## Website 1: https://example.com

* **What HTML tags are used on the page?**
    * `<!DOCTYPE html>`, `<html>`, `<head>`, `<title>`, `<meta>`, `<style>`, `<body>`, `<div>`, `<h1>`, `<p>`, and `<a>`.
* **What is the page title?**
    * "Example Domain" (found inside the `<title>` tag).
* **How many headings are there?**
    * There is exactly **1** heading on the page, which is an `<h1>` tag containing the text "Example Domain".

---

## Website 2: https://developer.mozilla.org

* **Find the navigation menu - what tag is it wrapped in?**
    * The main navigation menu is wrapped in a semantic `<nav>` tag (specifically with a class like `.main-nav`).
* **How is the search bar structured?**
    * It uses a semantic `<search>` wrapper or a `<form>` element acting as a search landmark. Inside, there is an `<input type="search">` field paired with a search icon/button.
* **What happens when you hover over links (check the styles)?**
    * When hovering over links, the browser triggers the `:hover` pseudo-class. The visual styles typically change the text color (e.g., changing to a brighter blue or an accent color) or apply an `text-decoration: underline` to clearly signify interactivity.

---

## Website 3: GitHub (https://github.com)

* **Identify 5 different HTML elements:**
    1.  `<header>` - Defines the global site header.
    2.  `<main>` - Encloses the primary content unique to the page.
    3.  `<button>` - Used for interactive, clickable actions (like dropdown toggles).
    4.  `<ul>` / `<li>` - Used to structure lists of repositories or navigation options.
    5.  `<img>` - Used to render user avatars and brand logos.
* **Find a form element and list its inputs:**
    * *Form picked:* The global header search form.
    * *Inputs/Controls found:*
        * `<input type="text">` (or `type="search"`) for typing the search query.
        * `<input type="hidden">` fields used for passing internal metadata/tokens.
* **Take a screenshot of the Elements panel:**
    * *(Note: Remember to use your operating system's screenshot tool to capture your actual browser's DevTools "Elements" tab panel and save it alongside your submission!)*
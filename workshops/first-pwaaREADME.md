---
name: 'First PWA'
description: 'Create your first offline and installable progressive web app.'
author: '@cwi'
---
In this workshop you will learn how to turn a web app into an offline capable and installable *progressive* web app.
## Prerequisites
You should have basic knowledge of the following:
 - HTML
 - CSS
 - Javascript
 - How webpages are fetched by the browser
## Getting started
We are going to be using repl.it, a cloud IDE that provides several languages. Click <a target="_blank" href="https://repl.it/languages/html">here</a> to open a basic HTML repl.
Once the project has loaded, add the following lines to your project just before the `</body>` tag:
```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/vue@2.6.12/dist/vue.js"></script>
```
> These two lines add jQuery and Vue.js to your project.<br>
> jQuery is a library that simplifies DOM traversal and event handling.<br>
> Vue.js is a javascript framework that focuses on ease of use and substitution, we will use this to create our base app.<br>

also, change the `<title>` tag content from repl.it to `Todo List`:
```html
<title>Todo List</title>
```
## Creating the Todo List app
We will have to 

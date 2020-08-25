# Explore the tech!
In yesterday's blog, I explained _HTML_, which presents the **structure** of web pages. Today, I'm going to dig deeper into _how_ the contents of web pages should look like. This is done using ***CSS***, which stands for Cascading Style Sheets. 
So, _let's get started!_

### 1. Introducing CSS:
So, what the CSS does is that it allows the developer to create rules that specify how the content of an element should appear. This will make web pages more attractive and appealing to the eye.
CSS works by associating rules with HTML elements. These rules tells the browser how the content of specified elements should be displayed on the screen. A _CSS rule_
contains 2 parts: a selector and a declaration. For example, in this CSS command, `p {font-family: Arial;}`, `p` is the **selector** and `font-family- is the **declaration**. 
Also, declarations contains 2 parts: property and value. `font-family` is the **property** and `Arial` is the **value**.
However, if there are 2 or more rules that apply to the same element, the rule is chosen based on the following:
* Last rule.
* Specifity.
* Improtant. `!important`

There are 2 ways to associate the **CSS** with the HTML file: _internal_ using `<style>` tag, and external using `<link>` tag to a separate `.css` file.


### 2. Color:
_We can all agree that colors can bring anything to life!_ In web development, **CSS** is responsible for specifying the colors of the web page. The _color_ property allows the developer to specify the color of text inside an element. Color can be specified in three ways: rgb values, hex codes and color names. the foreground color the page is sepcified using `color` property while using `background-color` for background color. For people to be able to read your content, it's important to ensure that there is enough contrast between any text and the background color. 
_Note: try to use a ***color picker*** tool that will make your life easier by helping you find the colors you want!_

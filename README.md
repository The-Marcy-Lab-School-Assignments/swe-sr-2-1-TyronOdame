# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/fullstack-curriculum/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

Do some research on semantic and non-semantic elements and share your findings. Your response should include:

- Examples of semantic and non-semantic tags
- The differences between semantic and non-semantic tags
- The benefits of using semantic tags (when possible)

### Response 1

An example of a semantic element would be <'article'>,<'footer'> and <'header'>. However, an example of non-semantic element would be <'div'> and <'span'>.
Semantic elements are elements that are easy to tell what they are doing. Its meant for anyone who is looking at the code to be able to tell what each element is doing. On the other hand, non-semantic elements are descriptive at all. Developers would have a hard time reading and understand what element is doing what.

## Prompt 2

Do some research on accessibility. What are some ways to make your website more accessible? Explain why it is important for developers to create websites that meet accessibility standards.

### Response 2

accessibility is making your website function for all people. For example, if someone is trying to visit your website and he or she is blind, you would add text on your photo using 'alt'. This would allow any text to speech feature on the viewers browser to read out a description about what the photo is about.

## Prompt 3

It is possible to add "inline" CSS styles to our html elements using the `style` attribute like so:

```html
<p style="color: red;">hello world</p>
```

While this is possible, it is a best practice to instead write styles in a separate CSS file. Provide at least one argument for why it _might_ be considered useful to write inline styles, and then provide a more compelling argument for writing styles in a separate CSS file.

### Response 3

Although this is not good practice, like you've motioned. One good argument would be if you just wanted to change the color of something really fast, I would argue that using inline CSS in the html file would save time because you would not need to create a CSS file.

## Prompt 4

Imagine you are teaching a brand new programmer a brief lesson about the `class` and `id` attributes in HTML as well as how to use them to style elements using CSS. Your lesson should have the following components:

- An explanation of the concept of "classes" and "ids" with an analogy.
- An example of the usage using an HTML code block and a CSS code block.
- An explanation of the syntax using the terms: **attribute**, **selector**

### Response 4

Class and ids are very simple to understand. One way you can think about it is that in a 'class' there are always more than 1 student in a class. The same logic applies here. You can assign the same class to more then one element in an html file. Unlike with an id, everyone has unique id numbers on there drivers licenses. Same logic also applies, every element would have only one unique id.

an example of an attributes in html:

`<a href='' alt=''>`
`<div id="main-content"></div>`

id is the attribute in the `<div>` and href is the attribute in the `<a>`

An example of selectors in CSS:

`p {
    color: blue;
}
`

`.text-large {
    font-size: 24px;
}
`
`p` being the selector and '.text-large' being the other selector.

## Prompt 5

The Document Object Model (DOM) API provides functions for manipulating HTML documents. It is possible to build an entire website using only JavaScript and the DOM API, however is that the best practice?

When building a website, how can I decide which content I should write using HTML/CSS and which content I should create using the JavaScript and the DOM API?

### Response 5

When it comes to building a website, I believe that it is best to use CSS/Html when you are trying to design your web page. Trying to customize a whole web page with JavaScript could put a lot of unnecessary complications on the process. In other words, you want to use HTML/CSS for static content and styling. JS/DOM is more for making your website interactive when people visit it. When users either click, hover, submit (etc), JS/HTML can help create those interactions. Or to put it simply, JS/DOM is better used for dynamic and interactive content

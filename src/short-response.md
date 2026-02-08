# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: HTML Structure

What is the difference between the `<head>` and `<body>` sections of an HTML document? What kind of content goes in each?

**Your Answer:**
The difference between the `<head>` and `<body>` sections of an HTML document is how they are rendered onto the webpage (visibility) and their purpose. The `<head>` section of an HTML document contains meta-data, or information about the website that isn’t shown on the webpage or visible to the user (links to `CSS`, webpage title, etc.), while the `<body>` section of an HTML document has all the elements, or content that is shown on the webpage and is visible to the user (text, images, headers, and nav). To summarize, the  `<head>`  gives the browser information about how to display the webpage, while the  `<body>` contains the content to display.


## Question 2: Semantic HTML

Why should we use semantic elements like `<header>`, `<main>`, and `<footer>` instead of using `<div>` tags for everything?

**Your Answer:**
We use semantic elements like `<header>`, `<main>`, and `<footer>` instead of using `<div>` tags for everything  because semantic elements have nametags that describe their purpose and the kind of content they contain compared to `<div>` tags that all share the same name, so they aren’t distinguishable from each other.  Having semantic elements make code easier to read for ourselves and other coders, assist screen readers and users with disabilities, and makes it easier for browsers to recognize our webpage structure.


## Question 3: CSS Selectors

Given the following HTML:

```html
<ul>
  <li class="vegetable">Carrots</li>
  <li class="vegetable">Broccoli</li>
  <li class="fruit" id="favorite">Mango</li>
</ul>
```

Write THREE different CSS rules:
1. One that makes ALL list items have a `yellow` background
2. One that makes only the vegetables have `green` text color
3. One that makes only the Mango `bold`

**Your Answer:**

```css
/* 1. One that makes ALL list items have a `yellow` background */
li {
background-color: yellow;
}
/* 2. One that makes only the vegetables have `green` text color*/
.vegetable {
color: green;
}
/* 3. One that makes only the Mango `bold`*/
#favorite {
font-weight: bold;
}
```


## Question 4: The Box Model

In your own words, explain the four parts of the CSS box model (content, padding, border, margin). What is the purpose of each part?

**Your Answer:**

The `CSS box model` is all over my grandmother's photo wall.  Each framing is an example of the `CSS box model`.  The photo itself is the `content`, or what is being displayed.  The `padding` is the backing behind the photo, which separates/gives space between the photo from the frame, which is the `border`.  Finally, the `margin` is the space between one framed photo and all the other photos on the wall.

## Question 5: Box-Sizing

What problem does `box-sizing: border-box` solve? Why do we include it in a CSS reset at the top of our CSS files?

**Your Answer:**


## Question 6: Display Property

What is the difference between `display: block`, `display: inline`, and `display: inline-block`? Give an example of when you might use `inline-block`.

**Your Answer:**


---
layout: essay
type: essay
title: A UI Framework, but Minus the Work
date: 2020-02-25
labels:
  - UI Frameworks
  - Semantic UI
---
## My First Encounter with UI Frameworks
Just a few days ago I had my first experience using a UI Framework.  In my software engineering course I learned how to use Semantic UI and within a week I recreated the visual aspects of various websites that looked complex and beyond my capabilities.  To my surprise, these websites were relatively simple to recreate using Semantic UI because it has various classes that are already built in that make it easier to create more visually pleasing buttons, images, menus, and more.  Semantic UI's syntax is similar to describing something in English, so picking up the language was not particularly difficult.  I am still shocked by the fact that I can create a dropdown menu by simply specifying the class as "ui dropdown".

## The Cons
Semantic UI amazed me, but there are always cons to everything.  Semantic UI's language is easy to catch onto because its syntax is similar to English language.  For example, if I wanted a small rounded image, I could simply define the class of the image to be "ui small rounded image" and the image would appear as such.  It's simple and requires little memorization, but because of this I often find myself adding any descriptive words to the class that are not a part of Semantic UI in hopes that it works.  This leaves me relying on guessing too much and forgetting what the Semantic UI capabilities actually are.  Also, while learning Semantic UI I began to rely on Semantic UI too much and I assumed it would do everything for me.  I forgot that Semantic UI is a great base to build off of, but if you want to get specific colors, styles, and sizes then using CSS in conjuction with Semantic UI is optimal.

## Why UI Framworks are Worth It
Despite the few negative aspects of Semantic UI, the pros weigh out the cons by a landslide.  As I mentioned before, it is not a difficult tool to learn.  It may take some time to explore all of the capabilities of Semantic UI, but it's worth it in the end when you're able to create beautiful websites with less effort.  When using raw HTML and CSS for everything, it can be difficult to work with the positioning, sizing, and shape of an image because each aspect of the image needs to have its own line of code that could involve exact values.  With Semantic UI I can easily change the look and position of the image with two descriptive words.  Imagine the difficulty of having to figure out how much percentage to round the edges of an image to make it look nice in CSS compared to the simplicty of adding the word "rounded" in the class name of the image.  This not only saves time, but it also helps software engineers edit and debug the code.  When the code has less numbers and symbols, it's easier for software engineers to analyze, read, and visualize the code.

## Making a Small Circular Image
Notice how using semantic UI did not require any extra lines of code in CSS and the class is easy for the average person to understand.

### Strictly CSS & HTML
```html
<img src="happy.jpg" alt="happy face picture">
```
```css
img {
  border-radius: 50%;
  width: 150px;
}
```

### Semantic UI
```html
<img class="ui small circular image" src="happy.jpg" alt="happy face picture">
```

## Overall
Semantic UI has opened a world of possibilities for me.  The ease of the syntax makes it less intimidating for new software engineers, so more people can step out of their comfort zone and create visually stunning websites.  I can't wait to learn other UI Frameworks and broaden my capabilities as a software engineer even more! 

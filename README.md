# 20-10-26 CSS Intro Lecture
Today's lecture will focus using CSS to style HTML elements. We will cover how to select elements and style common properties. 

### Set Up
1. copy the assignment git url in github after accepting the assignment
1. clone the assignment in the `html-css-basics` directory using `git clone COPIED URL`
1. open the assignment in VSCode
1. open the provided HTML file using `ctrl o` in the browser

### Linking files
1. create a new css file called `style.css`
2. link the css file to the html file using the `link` tag in the `head` - set the `rel` attribute to `stylesheet` and the `href` attribute to the css file path
```html
 <link rel="stylesheet" href="style.css">
```
3. check that the files are linked by setting the `background-color` property of the body to any color other than white/gray and refreshing the page

### Tag Selector
1. change the background of the webpage to gray using the body tag selector and setting the background-color property to gray
1. change the font of the webpage to a sans serif using the body tag selector and setting the font-family to sans-serif 
1. add spacing around the webpage content using the body tag selector and setting the margin to 5%
1. change the font color of the text inside the span element and the text of the link in the header to white using the span tag selector and the anchor element selector separated by a comma and setting the color to white
1. change the color of all paragraph element text to  dark green
1.  set the width of all images to 75% of their parent container and give all images at thick black border using the image tag selector 
1.  give all div elements a thin gray border with space between the div's content and the border and space between the bottom of the first div and the top of the second

### Class Selector
1. add a class, `callOutText` to the first paragraph element in the first and second div elements
1. add a class, `centerText` to the header and footer elements as well as the first paragraph in the second div element
1. change the font color of all elements with the class `callOutText` to dark blue
1. align the text of all elements with the class `centerText` to be centered

### ID Selector
1. add an id, `secondaryImg` to the second image element on the page
1. style the element with the class `secondaryImg` to be 50% of the width of it's container with a dark green border

### Referencing Children Elements
1. make the heading 3 text inside the header element italic by referencing it as a child element 

### Push File Changes in the Terminal
1. `git status` : check if file changes have been made
1. `git add -A` : stage changes for commit
1. `git commit -m "meaningful message"` : commit changes with appropriate message
1. `git push` : reflect local changes remotely 

### Resources
[Concept Documentation Info on HTML + CSS](https://github.com/cs-parttime-2020-fall/part-time-program-syllabus/blob/master/htmlCSS.md)


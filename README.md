# Code Refactor Challenge

Challenge 01 in the UT Coding Bootcamp

## Website

https://zachyarbrough.github.io/01-code-refactor/

![Screenshot of the website](assets/images/website-img.png?raw=true "Horiseon Website Screenshot")

## Prompt

AS A marketing agency\
I WANT a codebase that follows accessibility standards\
SO THAT our own site is optimized for search engines

## Things I changed

### HTML
Updated title to be more descriptive\
Updated all divs to more specific selectors\
Ensured that the hrefs work properly with the given IDs\
Added alt descriptions to the images, some image alts I left blank so page readers can still read them but they are unneccesary for the flow of the page\
Updated the header elements to be in order from h1 to h4

### CSS
Changed a div element to nav so that the css will still work properly\
Combined multiple classes due to repeated code\
Combined the font-family and added it to the body selector

## Requirements

GIVEN a webpage meets accessibility standards\
WHEN I view the source code\
THEN I find semantic HTML elements\
WHEN I view the structure of the HTML elements\
THEN I find that the elements follow a logical structure independent of styling and positioning\
WHEN I view the image elements\
THEN I find accessible alt attributes\
WHEN I view the heading attributes\
THEN they fall in sequential order\
WHEN I view the title element\
THEN I find a concise, descriptive title
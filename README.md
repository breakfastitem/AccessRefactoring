# Search Engine Optimization and Access Refactoring

## Intro
This github was about refactoring a source html, to make it more semantic. This includes adding alt tags to images and changing divs to more appropriate elements. None of these changes altered the apperance of the site.

## Preview
The site appears as follows.

![site-demo](./assets/images/site-preview.png)

## Live page

The page can be viewed at https://breakfastitem.github.io/AccessRefactoring/. It can also be viewed by opening index.html with a browser.

## ChangeLog
Added header and footer elements.

Changed div to nav for header nav bar.

Added alt tags to all images in html.

Added area tag to billboard class.

Added Section tags to all divs containg headers.

Changed footer header to h4 from h2.

Made title content specific to website.

Added Id to search-engine-optimization to allow navbar to work correctly.

Consolidated the css Classes to behave as classes not ids. For example changing benifit-lead etc.. to benifit because each benefit has the same style.

I left the billboard element as a div because I didn't feel that there was an appropiate html element for that type of object. It is a style trend to include a billboard image and there are no html elements designed for its purpose.
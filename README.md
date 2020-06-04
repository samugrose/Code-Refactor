code refactor readme:

For this code refactoring, I removed many divs with classes like "header", "footer", and others, replacing the names with HTML semantic tags that usually matched the class names in the originally provided HTML. I removed a closing img tab from one of the <img> elements, since img is a self closing element. Furthermore, I added alt text describing the images in the HTML, and added comments describing the content sections of the HTML.

In the CSS, I reduced the redundancy by combining multiple classes that had the same content, making the code much easier to understand. I also changed the .seo class into an id, since it was only being applied once in the CSS. 
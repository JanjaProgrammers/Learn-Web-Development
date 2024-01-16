## Nesting elements

- HTML5 has some elements that identify different content areas. These elements make your HTML easier to read and help with Search Engine Optimization (SEO) and accessibility.
- Semantic elements like `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>` are introduced in HTML5 to add meaning and structure to the content.

- Put the h1, h2, comment, and p elements inside the main element. This is called nesting. Nested elements should be placed two spaces further to the right of the element they are nested in. This spacing is called indentation, and it is used to make HTML easier to read.

You can put elements inside other elements too. If we wanted to state that our cat is very grumpy, we could wrap the word "very" in a `<strong>` element, which means that the word is to be strongly emphasized.

## Images

A picture is worth a thousand words! Web pages with images get more views, rank higher in search results, and get shared more on social media. In this lesson, you'll learn to add images to your pages.

The HTML `<img>` tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The `<img>` tag creates a holding space for the referenced image.

### Void Elements

The `<img>` tag is empty; it contains attributes only and does not have a closing tag. Some elements have no content and are called void elements. Another example is the `<br>` element.

The `<img>` tag has two required attributes:

- `src` - Specifies the path to the image
- `alt` - Specifies an alternate text for the image `<img src="image url" alt="alternatetext">`

This contains two attributes, but there is no closing `</img>` tag and no inner content. This is because an image element doesn't wrap content to affect it. Its purpose is to embed an image in the HTML page in the place it appears.

There are two ways to specify the URL in the `src` attribute:

1. **Absolute URL** - Links to an external image hosted on another website. Example: `src="https://www.w3schools.com/images/img_girl.jpg"`.

   - Notes: External images might be under copyright, so ensure proper permissions.

2. **Relative URL** - Links to an image hosted within the website. If the URL begins without a slash, it's relative to the current page. Example: `src="img_girl.jpg"`. If the URL begins with a slash, it's relative to the domain. Example: `src="/images/img_girl.jpg"`.
   - **Tip: It is almost always best to use relative URLs. They will not break if you change the domain.**

### The width and height Attributes

The `<img>` tag should also contain the `width` and `height` attributes, specifying the width and height of the image (in pixels):

Example:

```html
<img src="img_girl.jpg" width="500" height="600" />
```

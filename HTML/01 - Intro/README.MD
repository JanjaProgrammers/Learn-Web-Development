# Intro to HTML

- HTML (HyperText Markup Language) is a markup language that defines the structure of a web page and its content.

- HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way or act a certain way.

- An element is a part of a webpage. In HTML, an element may contain a data item or a chunk of text or an image, or perhaps nothing. A typical element includes an opening tag with some attributes, enclosed text content, and a closing tag.

### The main parts of our element are as follows:

- The opening tag: This consists of the name of the element, wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect.

- The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.

- The content: This is the content of the element.

- The element: The opening tag, the closing tag, and the content together comprise the element.

HTML elements have opening tags like `<h1>` and closing tags like `</h1>`.

The text for an element goes between its opening and closing tags.
`<h1>Text Goes Here</h1>`

## Headings

- The h1 through h6 heading elements are used to signify the importance of content below them. The lower the number, the higher the importance, so h2 elements have less importance than h1 elements. It's a good practice to use h1 for the main heading of your page and then use h2, h3, etc., for subsections.

## Paragraphs

- The p element is used to create a paragraph of text on websites.

## Comments

- Commenting allows you to leave messages without affecting the browser display. Comments help other humans to read your code. It also allows you to make code inactive. A comment in HTML starts with

```
<!-- contains any number of lines of text, and ends with -->
```

## Attributes

Attributes contain extra information about the element that you don't want to appear in the actual content.

- All HTML elements can have attributes.
- Attributes provide additional information about elements.
- Attributes are always specified in the start tag.
- Attributes usually come in name/value pairs like: `name="value"`.
- Some attributes have no value, such as `required`.

Attributes that set a value always have:

- A space between it and the element name (or the previous attribute if the element already has one or more attributes).
- The attribute name followed by an equal sign.
- The attribute value wrapped by opening and closing quotation marks.

### style Attribute

The HTML style attribute is used to add styles to an element, such as color, font, size, and more.
Setting the style of an HTML element can be done with the style attribute.
The HTML style attribute has the following syntax:

```html
<tagname style="property:value;"></tagname>
```

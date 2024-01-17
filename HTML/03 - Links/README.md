# Links

HTML links are hyperlinks. You can click on a link and jump to another document. When you move the mouse over a link, the mouse arrow will turn into a little hand.

**_Note: A link does not have to be text. A link can be an image or any other HTML element!_**

The HTML `<a>` tag defines a hyperlink. It has the following syntax:
`<a href="url">link text</a>`
The most important attribute of the `<a>` element is the `href` attribute, which indicates the link's destination. The link text is the part that will be visible to the reader. Clicking on the link text will send the reader to the specified URL address.

By default, links will appear as follows in all browsers:

- An unvisited link is underlined and blue.
- A visited link is underlined and purple.
- An active link is underlined and red.

By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link. The `target` attribute specifies where to open the linked document.

The `target` attribute can have one of the following values:

- `_self` - Default. Opens the document in the same window/tab as it was clicked.
- `_blank` - Opens the document in a new window or tab.
- `_parent` - Opens the document in the parent frame.
- `_top` - Opens the document in the full body of the window.

### HTML Links - Use an Image as a Link

To use an image as a link, just put the `<img>` tag inside the `<a>` tag:

```html
<a href="default.asp">
  <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;" />
</a>
```

### Link to an Email Address

Use `mailto:` inside the href attribute to create a link that opens the user's email program (to let them send a new email):

```
<a href="mailto:someone@example.com">Send email</a>
```

### Link Titles

The `title` attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element.

```
<a href="https://www.janjaprogrammers.com/" title="Go to JP">Visit our Website</a>
```

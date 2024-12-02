# HTML Basics

This documentation covers the fundamental structure of an HTML document and also
includes some commonly used HTML tags.

## Structure

Here is the basic structure of an HTML document:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Website</title>
  </head>
  <body>
    <p>Hello world!</p>
  </body>
</html>
```

* `<!DOCTYPE html>` - Declares the document type and version of HTML.
* `<head></head>` - Contains metadata (data about the document) that is not displayed on the webpage.
* `<body></body>` - Contains the main content of the webpage that is displayed to users.

## HTML Tags

HTML is built using tags, which define the structure and content of the webpage. Most tags follow this format:

* An opening tag: `<tag_name>`
* A closing tag: `</tag_name>`

```html title="Example"
<h1>My Website</h1>
```

Some tags are **self-closing** and do not require a closing tag. These are
typically used for elements that do not have content.

```html title="Example"
<input type="text">
<img src="image.jpg" alt="Example image">
```

!!! note

    HTML files must have the `.html` file extension (e.g., `index.html`).

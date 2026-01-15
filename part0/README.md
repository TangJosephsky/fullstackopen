# Note

## HTML

An example of a basic HTML document structure:
```html
<!doctype html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>My test page</title>
  </head>
  <body>
    <img src="" alt="My test image" />
  </body>
</html>
```
Some essential HTML tags include:
- `<h1>` to `<h6>`: Headings
- `<p>`: Paragraph
- `<a>`: Anchor (link), `<a href="URL">...</a>`, where `href` stands for "hypertext reference"
- `<img>`: Image
- `<div>`: Division or section
- `<list>`: List (ordered and unordered)


## CSS
An example of basic CSS styling:
```css
p {
    color: blue;
}
```

To apply CSS to an HTML document, you can use the `<link>` tag in the `<head>` section:
```html
<link rel="stylesheet" href="styles.css" />
```

The box model in CSS consists of:
- Content: The actual content of the element, including text and images
- Padding: Space between the content and the border
- Border: The edge surrounding the padding (if any)
- Margin: Space outside the border, separating the element from other elements

## HTML Forms
An example of a simple HTML form:
```html
<form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" />
    <input type="submit" value="Submit" />
</form>
```
The `for` attribute in the `<label>` tag associates the label with the corresponding input field by matching the `id` of the input.


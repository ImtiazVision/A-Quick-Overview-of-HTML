### `<p>`

The paragraph tag is often used for blocks of text (but they may sometimes include other paragraph-related elements such as images). As an example: `<p> This is a paragraph</p>`.

### Heading Tags 

HTML tags are represented as `<h1>` to `<h6>`. The top level heading is `<h1>`, the secondary subheading is `<h2>`, and so on. As an example:
  `<h1>Primary Heading</h1>`
  
  `<h2> Secondary Heading</h2>`
  
### `<img>` tag

The image tag is an empty tag that should always have two main attributes:
  - **src**: The path to the image, either relative or absolute.
  - **alt**: Alternative text to be used with screen readers or any time the image cannot be displayed.
For example, `<img src="img/demo.jpg" alt="demo" />`

### `<a>` tag

The anchor tag, which is used to connect to other pages. This tag should have a href property providing the path to the linked page (absolute or relative). As an example:

  `<a href="https://google.com">Google</a>` 

### `<ul>` tag

The unordered list tag is used for a list when the order is irrelevant. Most browsers will display this as a bulleted list by default.
The unordered list may have any number of `<li>` tags. As an example:
```
<ul>
    <li>Milk</li>
    <li>Cheese</li>
    <li>Fruit</li>
    <li>Fish</li>
</ul>
```

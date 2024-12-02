# Examples

## Paragraphs

```html
<p>Hello world!</p>
<p>Hello user!</p>
```

<iframe src="../previews/paragraphs.html" frameborder="0" width="100%"></iframe>

## Headings

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

<iframe src="../previews/headings.html" frameborder="0" width="100%"></iframe>

## Text Formatting

```html
<b>Bold text</b><br>
<strong>Strong text</strong><br>
<i>Italic text</i><br>
<em>Emphasized text</em><br>
<mark>Marked text</mark><br>
<small>Smaller text</small><br>
<del>Deleted text</del><br>
<ins>Inserted text</ins><br>
Subscript text <sub>sub</sub><br>
Superscript text <sup>sup</sup>
```

<iframe src="../previews/text-formatting.html" frameborder="0" width="100%"></iframe>

## Break Line

Written as `<br>`

=== "With"

    ```html
    <b>Bold text</b><br>
    <strong>Strong text</strong><br>
    <i>Italic text</i>
    ```
    
    <iframe src="../previews/with-br.html" frameborder="0" width="100%"></iframe>

=== "Without"

    ```html
    <b>Bold text</b>
    <strong>Strong text</strong>
    <i>Italic text</i>
    ```
    
    <iframe src="../previews/without-br.html" frameborder="0" width="100%"></iframe>

## Image

```html
<img src="/assets/cat.png" alt="cat sitting on floor">
```

<img src="../assets/cat.png" alt="cat sitting on floor">

## Ordered Lists

```html
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
</ol>
<ol type="a">
  <li>Item 1</li>
  <li>Item 2</li>
</ol>
<ol type="A">
  <li>Item 1</li>
  <li>Item 2</li>
</ol>
<ol type="i">
  <li>Item 1</li>
  <li>Item 2</li>
</ol>
<ol type="I">
  <li>Item 1</li>
  <li>Item 2</li>
</ol>
```

<iframe src="../previews/ordered-list.html" frameborder="0" width="100%"></iframe>

## Unordered Lists

```html
<ul type="disc"> <!-- (1)! -->
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
<ul type="square">
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
<ul type="circle">
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

1.  `type="disc"` is the default type for unordered list.

<iframe src="../previews/unordered-list.html" frameborder="0" width="100%"></iframe>

## Description List

```html
<dl>
  <dt>Item 1</dt>
  <dd>Description 1</dd>
  <dt>Item 2</dt>
  <dd>Description 2</dd>
  <dt>Item 3</dt>
  <dd>Description 3</dd>
</dl>
```

<iframe src="../previews/description-list.html" frameborder="0" width="100%"></iframe>

## Nested List

```html
<ul>
  <li>
    Files
    <ol>
      <li>Open file</li>
      <li>Create file</li>
      <li>Rename file</li>
      <li>Delete file</li>
    </ol>
  </li>
  <li>
    Topics
    <ol type="a">
      <li>Cat</li>
      <li>Dog</li>
      <li>Rabbit</li>
      <li>Lizard</li>
    </ol>
  </li>
</ul>
```

<iframe src="../previews/nested-list.html" frameborder="0" width="100%"></iframe>

## Font

```html
<p>
  <font face="Sans-Serif">Hello world!</font>
</p>
<p>
  <font face="Serif">Hello world!</font>
</p>
<p>
  <font face="Monospace">Hello world!</font>
</p>
```

<iframe src="../previews/font.html" frameborder="0" width="100%"></iframe>

!!! tip

    Visit this [link](https://www.w3schools.com/cssref/css_websafe_fonts.php) to see the list of available fonts.

## Fieldset and Legend

```html
<fieldset>
  <legend>Fieldset Example</legend>
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nam, facere.</p>
</fieldset>
```

<iframe src="../previews/fieldset-and-legend.html" frameborder="0" width="100%"></iframe>

## Inputs

```html
<input type="text" placeholder="Enter a text"><br>
<input type="email" placeholder="Enter your email"><br>
<input type="password" placeholder="Enter your password"><br>
<input type="radio"> Item 1<br>
<input type="radio"> Item 2<br>
<input type="radio"> Item 3<br>
<input type="checkbox"> Item 1<br>
<input type="checkbox"> Item 2<br>
<input type="checkbox"> Item 3<br>
```

<iframe src="../previews/inputs.html" frameborder="0" width="100%"></iframe>

## Select

=== "With pre-select"

    ```html
    <select>
      <option value="1">Item 1</option>
      <option value="2">Item 2</option>
      <option value="3" selected>Item 3</option>
      <option value="4">Item 4</option>
    </select>
    ```
    
    <iframe src="../previews/select-1.html" frameborder="0" width="100%"></iframe>

=== "Without pre-select"

    ```html
    <select>
      <option value="1">Item 1</option>
      <option value="2">Item 2</option>
      <option value="3">Item 3</option>
      <option value="4">Item 4</option>
    </select>
    ```
    
    <iframe src="../previews/select-2.html" frameborder="0" width="100%"></iframe>

## Anchor

```html
<a href="https://angeloyana.github.io/html-docs">Go to Homepage</a><br>
<a href="https://angeloyana.github.io/html-docs/css-properties">Learn CSS</a>
```

<iframe src="../previews/anchor.html" frameborder="0" width="100%"></iframe>

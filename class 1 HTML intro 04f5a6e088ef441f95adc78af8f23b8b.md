# class 1 HTML intro

abbreviation…uses to define an abbreviation or acronym 

```html
<abbr tittle="hyper text markup language">HTML</abbr>
```

icon…to add icon 

```html
<i>Arrow</i>
```

action….defines the action to be performed when the form is submitted

```html
<form action="/action-page.php"></form>
```

target…..specifies where to display the response that is received after submitting the form

```html
<form action="/action_page.php" target="_blank">
```

post message….used to post a message back to the html page 

```jsx
function timedCount() {
  i = i + 1;
  postMessage(i);
  setTimeout("timedCount()",500);
}
```

iframe….to brink contents from other resources 

```html
<iframe src="url" title="description"></iframe>
```

aside…..defines content aside form the content

```html
<aside>school</aside>
```

blockquote….defines a section that is quoted from another source 

```html
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 60 years, WWF has worked to help people and nature thrive. 
As the world's leading conservation organization, WWF works in nearly 100 countries.
 At every level, we collaborate with people around the world to develop and deliver 
innovative solutions that protect communities, wildlife, and the places in which they 
live.
</blockquote>
```

[forms](https://www.notion.so/forms-d5159a48da6241fcba1a20034fa3c48b?pvs=21)

`<picture>` element allows you to define different images for different browser window sizes.

```html
<picture>
<source srcset="img_smallflower.jpg" media="(max-width: 600px)">
</picture>
```

`<cite>` tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.)

```jsx
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
```

`<bdo>` tag is used to override the current text direction:

```jsx
<bdo dir="rtl">This text will be written from right to left</bdo>
```

"_blank" to open the linked document in a new browser window or tab:

```html
<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>
```

Use `mailto:` inside the `href` attribute to create a link that opens the user's email program (to let them send a new email):

```html
<a href="mailto:someone@example.com">Send email</a>
```

The `<fieldset>` tag is used to group related elements in a form.

```html
<form action="/action_page.php">
  <fieldset>
    <legend>Personalia:</legend>
    <label for="fname">First name:</label>
    <input type="text" id="fname" name="fname"><br><br>
    <label for="lname">Last name:</label>
    <input type="text" id="lname" name="lname"><br><br>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email"><br><br>
    <label for="birthday">Birthday:</label>
    <input type="date" id="birthday" name="birthday"><br><br>
    <input type="submit" value="Submit">
  </fieldset>
</form>
```

The `<canvas>` tag is used to draw graphics, on the fly, via scripting (usually JavaScript).

```html
<canvas id="myCanvas">
Your browser does not support the canvas tag.
</canvas>
```
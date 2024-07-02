# Assignment - 2 Answers

1. **What is the Shortcut Emmet Used to Create boilerplate of HTML?**
   The Emmet shortcut to create the boilerplate of an HTML file is `HTML:5`.

2. **What is DOCTYPE in Html?**
   `<!DOCTYPE html>` is a declaration that tells the web browser about the version of HTML used in the document. It helps the browser to render the page correctly.

3. **What is Void Element and Example for Void Elements?**
   A void element is an HTML element that does not have any content and does not require a closing tag. Examples include `<br>`, `<img>`, `<input>`, `<meta>`, and `<link>`.

4. **What is Different Element and Attributes?**
   - **Element**: An element is a part of the HTML document that defines the structure and content. For example, `<p>` is a paragraph element.
   - **Attributes**: Attributes provide additional information about an element and are defined within the opening tag. For example, `src` in `<img src="image.jpg">` is an attribute.

5. **What is Html Entries and Why is it need in HTML?**
   HTML entities are used to display reserved characters in HTML, ensuring they are interpreted as text rather than HTML code. For example, `&lt;` represents `<` and `&gt;` represents `>`.

6. **What are meta tag and why is it used?**
   Meta tags provide metadata about the HTML document. They are used for specifying the character set, viewport settings, keywords, description, author of the document, and other metadata. For example, `<meta charset="UTF-8">` specifies the character encoding.

7. **What is the best way to add images in Website?**
   The best way to add images to a website is by using the `<img>` tag with a proper `src` attribute pointing to the image's URL, whether it's a local path or a CDN link.
    For better performance and loading times, using optimized images and CDN-hosted images is recommended.
    Example for CDN: Imagekit.io



## Assignment - 7 [Self Assignment] Answers:

# HTML

## 💡 WHAT IS HTML

HTML (HyperText Markup Language) is the standard markup language used to create web pages. It describes the structure of a web page using a series of elements and tags, which tell the browser how to display the content.

## 💡 WHY HTML IS USED

HTML is used to:

1. Structure content on the web.
2. Define elements such as headings, paragraphs, links, images, and more.
3. Create web pages that can be linked to one another.
4. Provide a foundation upon which CSS (Cascading Style Sheets) and JavaScript can build more complex and interactive websites.

## 💡 What is Emmet & List 5 Emmet

Emmet is a plugin for many popular text editors which greatly improves HTML & CSS workflow by providing shorthand syntax to generate HTML and CSS code quickly.

Five common Emmet abbreviations:
1. `HTML:5` - Generates a basic HTML5 boilerplate.
2. `ul>li*5` - Creates an unordered list with five list items.
3. `div.container>div.row>div.col*3` - Creates a div with class "container" containing a div with class "row" which in turn contains three divs with class "col".
4. `a[href="http://example.com"]{Example}` - Creates an anchor tag with an href attribute and text content.
5. `form>input[type="text"]+input[type="submit"]` - Creates a form with a text input and a submit button.

## 💡 SHORT CUT CREATE of Emmet Boiler plate of HTML

To create a boilerplate HTML document using Emmet, you simply type `HTML:5` and then press `Tab` or `Enter` (depending on your text editor). This will generate a complete HTML5 document structure.

## 💡 WHAT STRUCTURE OF HTML

The basic structure of an HTML document includes:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
  </body>
</html>```

## What is the `<head>` Tag
The `<head>` tag contains meta-information about the HTML document. It includes elements such as:

- `<title>`: Specifies the title of the document, shown in the browser's title bar or tab.
- `<meta>`: Provides metadata such as character set, author, and description.
- `<link>`: Links to external resources like stylesheets.
- `<style>`: Contains internal CSS styles.
- `<script>`: Links to external JavaScript files or includes inline JavaScript.

## What is the `<body>` Tag
The `<body>` tag contains the content of the HTML document. This is where all the visible elements of the webpage go, such as:

- Headings (`<h1>` to `<h6>`).
- Paragraphs (`<p>`).
- Links (`<a>`).
- Images (`<img>`).
- Lists (`<ul>`, `<ol>`, `<li>`).
- Tables (`<table>`, `<tr>`, `<td>`).
- Forms (`<form>`, `<input>`, `<textarea>`).

## Important HTML Elements or Tags
- `<a>`: The anchor tag is used to create hyperlinks, which are essential for navigation between web pages.
- `<img>`: The image tag embeds images in a webpage, enhancing visual appeal and providing visual information.
- `<div>`: The division tag is a container element used to group and style sections of a webpage.

## Difference Between Elements and Tags in HTML
**Tags**: Tags are the building blocks of HTML. They are enclosed in angle brackets, such as `<div>`, `<p>`, or `<a>`. Tags are used to define the start and end of an element.

**Elements**: Elements are the complete structure from the opening tag to the closing tag, including the content in between. For example, `<p>This is a paragraph.</p>` is a paragraph element, consisting of the opening tag `<p>`, the content `This is a paragraph.`, and the closing tag `</p>`.

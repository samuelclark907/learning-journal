
# CSS + Color



## `<link>`

The `<link>` element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an empty element (meaning it does not need a closing tag), and it lives inside the `<head>` element. 

It should use three attributes:

- "href" - This specifies the path to the CSS file (which is often placed in a folder called css or styles).
- "type" - This attribute specifies the type of document being linked to. The value should be text/css.
- "rel"- This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.

## `<style>`


- You can also include CSS rules within an HTML page by placing them inside a `<style>` element, which usually sits inside the `<head>` element of the page.

- When building a site with more than one page, you should use an external CSS style sheet.

 The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:

- rgb values - These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)

 - hex Codes - These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80

- Color names - There are 147 predefined color names that are recognized by browsers. For example: DarkCyan

## HSL

- hue - This is expressed as an angle (between 0 and 360 degrees).

- saturation - This is expressed as a 
percentage.

- lightness - This is expressed as a percentage with 0% being white, 50% being normal, and 100% being black.

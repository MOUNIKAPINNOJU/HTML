# HTML 

<h1>Table of Content :</h1>
<ol>
    <li>Paragraph Element</li>
    <li>Heading Element</li>
    <li>Lists in HTML</li>
        <ul>
            <li>Unordered list</li>
            <li>Ordered list</li>
            <li>Ordered list revered</li>
        </ul>
    <li>HTML Attributes</li>
    <li>Anchor Element</li>
    <li>Image Element</li>
    <li>Break Tag</li>
    <li>Bold, Italic, Underline Tags</li>
    <li>Comments in HTML</li>
    <li>Inline/Block Element</li>
    <li>Div Element</li>
    <li>Span Element</li>
    <li>Hr Tag</li>
    <li>Sub & Sup Tags</li>
        <ul><li>Practice Qs 4</li></ul>
    <li>Semantic Markup</li>
        <ul><li>Practice Qs 6</li></ul>
    <li>HTML Entities</li>
        <ul><li>Practice Qs 5</li></ul>
    <li>Emmet</li>
    <h4>Assignmet Questions</h4>
    <li>Tables in HTML</li>
    <li>Semantics in Tables</li>
        <ul><li>Practice Qs 7</li></ul>
    <li>Colspan & Rowspan Attributes</li>
    <li>Forms in HTML</li>
        <ul><li>Practice Qs 7</li></ul>
    <li>Action Attributes</li>
    <li>Form Elements</li>
    <li>Action Attributes</li>
    <li>PlaceHolder</li>
    <li>Label</li>
    <li>Button</li>
    <li>Name Attribute</li>
        <ul><li>Practice Qs 8</li></ul>
    <li>Checkbox, Radio, Select, Range, Text Area</li>
    
    
</ol>

## What is HTML? 
HyperText Markup Language

## HTML Elements
Standard Elements that browser recognizes: 

Paragraph

Heading

Image

The Component used to design the structure of websites are called HTML Tags.
### <u> Paragraph Element</u>
The `<p>` HTML element represents a paragraph.

`<p>` opening tag

`</p>` closing tag

### <u> Heading Elements</u>
The `<h1>` to `<h6>` HTML elements represent six levels of section headings.

`<h1>` is the highest section level and `<h6>` is the lowest.
### <u> Lists in HTML</u>
Unordered List :

`<ul> </ul>` represents unordered list

`<li> </li>`represents list elements 

Below represents unordered list.
<ul>
    <li>Bread</li>
    <li>Butter</li>
    <li>Jam</li>
</ul>

Ordered List :

`<ol> </ol>` represents ordered list

`<li> </li>`represents list elements 

Below represents ordered list.
<ol>
    <li>Bread</li>
    <li>Butter</li>
    <li>Jam</li>
</ol>

Below represents ordered list in reverse order.
<ol reversed>
    <li>Bread</li>
    <li>Butter</li>
    <li>Jam</li>
</ol>

### <u> HTML Attributes</u>
Attributes are used to add more information to the tag.

`html lang="en"`
### <u> Anchor Elements</u>
Used to add links to your page.

`<a href="https://google.com>Google</a>`

### <u>Image Element</u>
Used to add image to your page.


`<img src="image.png" alt="Random Image">`
### <u> Break Tag</u>
Used to add next line(line breaks) to your page

`<br>` represents break tag

### <u> Bold, Italic & Underline Tags</u>
Used to highlight text in your page.

`<b> </b>`   <b> Bold</b>

`<i> </i>`   <i> Italic</i>

`<u> </u>`   <u>underline</u>

### <u> Comments in HTML </u>
This is part of code that should not be parsed.

`<!-- This is an HTML Comment-->`

<!-- This is an HTML Comment which is not parsed-->
### <u>Inline v/s Block</u>
Block Elements:
Takes up the full-width available(whole block)
Start from new line

Example: Heading Element, Paragraph Element.

Inline Elements: Takes up only necessary width.
Don't start from new line

Example: Anchor Tag, Image Element.

### <u>Div Element</u>
Div is a container used to hold other HTML elements or group elements together.(also called as content division element)

It is a block Element.

`<div> </div>` is used to represent the element

### <u>Span Element</u>
Span is also a generic container used to hold other HTML elements or group of elements together. It is an inline Element.

`<span> </span>` is used to represent the element.

### <u>Hr Tag</u>
Horizontal Rule Element.

`<hr>` is used to represent the tag,

### <u>Sub & Sup Tag</u>
SubScript and SuperScript

a<sup>2</sup> = b<sup>2</sup> + c<sup>2</sup>  superscript <br>

H<sub>2</sub>O  subscript

<h3>Practice Qs 4:</h3>
<p>Pythagoras theorem says a<sup>2</sup> + b<sup>2</sup> = c<sup>2</sup>
<p>Formula for glucose is C<sub>6</sub>H<sub>12</sub>O<sub>6</sub>

### <u>Semantic Markup</u>
It is the markup that relates to the meaning of content.

Semantic : A semantic element clearly describes its meaning to both browser and the developer.

Example:`<form>, <table>, <article>, <header>, <main>, <footer>, <nav>, <section>, <aside>` - clearly defines its content.

Non-Semantic: `<div>, <span>` - Tells nothing about its content.
<h3>Practice Qs 6</h3>
Add semantic markup to your portfolio page.
    <ul>
        <li>header</li>
        <li>footer</li>
        <li>sections </li>
    </ul>


Refer `myPortfolio.html` for this code.

### <u>HTML Entities</u>
<ul>
    <li>An HTML entity is a piece of text("String") that begins with an ampersand(&) and ends with a semicolon(;)</li>
    <li>used to display <i>reserved characters</i> (which would otherwise be interpreted as HTML code), and <i>invisible characters</i> (like non-breaking spaces)</li>
    <li>can also use in place of characters that are difficult to type with a standard keyboard.</li>
    <li>browser interprets them & renders correct character.</li>
</ul>

 & `&amp;` Interpreted as the beginning of an entity or character reference.

 < `&alt;` Interpreted as the beginning of a tag.

> `&gt;` Interpreted as the ending of a tag.

" `&quot;` Interpreted as the beginning and end of an attribute's value.

<h3>Practice Qs 5</h3>
Print the sentence using suitable cloud & rain entities.

 Refer `index.html` file for the code.

 ### <u>Emmet</u>
 It is an essential development tool that helps you quickly create repetitive structures like lists, tables, or ordered elements with minimal typing.

 Child : `>`

 Sibling : `+`

 Climb-up : `^`

 Multiplication : `*`

 Item numbering : `$`

 <h3>Assignmet Questions</h3>

 <p>Today is the 12<sup>th</sup> of September and 2<sup>4</sup> = 16 always</p>

 copyright entity name : `&copy;` &copy;

 Trademark entity name : `&reg;` &reg;

 ### <u>Tables in HTML</u>
 Tables are used to represent real life table data.

 `tr` used to display table row.

 `td` used to display table data.

 `th` used to display table header.

 Refer `index.html` for example code.

 ### <u>Semantics in Tables</u>

 `<thead>` to wrap table header

 `<tbody>` to wrap table body

 `<tfoot>` to wrap table footer

 Refer `index.html` for example code. 

 ### <u>Colspan & Rowspan Attributes</u>
 used to create cells which spans over multiple rows or columns.

 rowspan -- attribute specifies how many rows a table cell should span, determing its vertical position.

 colspan -- attribute specifies the number of columns a cell should span, determing its horizontal position.

 <h3>Practice Qs 7</h3>

 Refer `index.html` for this code.

 ### <u>Forms in HTML</u>
Forms are used to collect data from the user.

`<form> </form>` 

### <u>Action Attribute</u>
<i>Action attribute</i> is used to define what action needs to be performed when a form is submitted or where the form data should be sent.

`<form action="/action.php"`

`<form action="/action"`

### <u>Form Elements</u>
Input : Used to create multiple form controls. There are multiple types of inputs that can be created using type attribute.

`<input type = "text">`

`<input type = "password">`

`<input type = "number">`

`<input type = "time">`

`<input type = "color">`

Refer `index.html` for code.

### <u>Placeholder attribute</u>
`<input type="text" placeholder = "Enter Name">` 

### <u>Label attribute</u>
Label element represents a caption for an item in a user interface.

### <u>Button Element</u>
It is a type attribute

`<button type="submit"> submit </button>`

`<button type="button"> do something </button>`

`<button type="reset"> do something </button>`

### <u>Name Attribute</u>
Name of the form control. Submitted with the form as part of a name/value pair.

`<input type="text" placeholder="enter name" id="username" name="username"/>`

<h3>Practice Qs 8</h3>
Create a search option that redirects its search request to google.


Refer `index.html` for code.

### <u>Checkbox, Radio, Select, Range, Text Area</u>

Refer `index.html` for code

















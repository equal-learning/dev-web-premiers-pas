#  HyperText Markup Language (HTML)

#### HTML: HyperText Markup Language

Concept: 

Designed by physicist Tim Berners-Lee, in 1980
A Markup Language - Include directives with content
Directives can dictate presentation or describe content
Examples: <i>italics word</i>, <title>Title words</title> Example of a declarative language

Approach
1. Start with content to be displayed
2. Annotate it with tags . HTML uses < > to denote tags

####  HTML Evolution  
Forked into HTML and XHTML (XML-based HTML).  
Today <b>XHTML<b> is widely used, so we will focus on it.

####  Basic Syntax rules for XHTML
Document: hierarchical collection of elements, starting with &lt;html&gt;  
  
Element: start tag, contents, end tag  
Elements may be nested  
Every element must have an explicit start and end  
Can use &lt;foo /&gt; as shorthand for &lt;foo&gt;&lt;/foo&gt;  
Start tags can contain attributes:
```
<img src="face.jpg">
<input type="text" value="94301" name="zip">
<div class="header">
```

####  Example XHTML document structure
````html
<?xml version="1.0" encoding="utf-8"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
    "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en">
  <head>
    <title>Hello World</title>
  </head>
  <body>
    <p>Hello world!</p>
  </body>
</html>
 
````

####  Common usage XHTML tags

&lt;p&gt; New paragraph  
&lt;br&gt; Force a line break within the same paragraph  
&lt;h1&gt;, &lt;h2&gt;, ... Headings  
&lt;b&gt;, &lt;&i&gt; Boldface and italic   
&lt;pre&gt; Typically used for code: indented with a fixed-width font,  
      spaces are significant (e.g., newlines are preserved)  
&lt;img&gt; Images
&lt;a&gt; href="..."&gt;  Hyperlink to another Web page  
&lt;!-- comments --&gt;  Comment tags  




 



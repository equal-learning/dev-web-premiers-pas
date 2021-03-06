#  HyperText Markup Language (HTML)

#### HTML: HyperText Markup Language

Concept: 

* Designed by physicist <b>Tim Berners-Lee </b>, in 1980

* A Markup Language - Include directives with content

* Directives can dictate presentation or describe content

Examples: <i>italics word</i>, <title>Title words</title> Example of a declarative language

Approach:

1. Start with content to be displayed
2. Annotate it with tags . HTML uses < > to denote tags

#### HTML tags

Tags can provide: Meaning of text:
<ul>
<li>  &lt;h1&gt means &lt;/h1&gt means top-level heading </li>
<li>  &lt;ul&gt means &lt;/li&gt for unordered (bulleted) list </li>
<li>  &lt;img&gt means &lt;/img&gt to display images </li>
<li>  &lt;i&gt means &lt;/img&gt to format information for italic </li>
<li> so on ... more than <b>100</b> tags available </li>
</ul>

Even though there are so many tags only handful of them are used most of the time.
Some frequently used tags : &lt;h1&gt;,  &lt;i&gt;, &lt;b&gt;, &lt;a&gt; &lt;ul&gt;, &lt;div&gt; ...

Tags can have tags inside (nesting supported) - Document forms a tree :
Ex -

```
<body>
    <h1> ...... <h1>
    <p> ..... </p>
<body>

```

### Example of HTML - Start with raw content text

Introduction

Consumption of following things is bad for health.

cannabis  
cigarette  
alcohol  


### Example of HTML - Annotate with tags


```
<h1> Introduction <h1>
<p>
    Consumption of following things is bad for health.
</p>
<ul>
<li>cannabis</li>
<li>cigarette</li>
<li>alcohol<li>
<ul>
```
---

####  HTML Evolution  
Forked into HTML and XHTML (XML-based HTML).  
Today <b>XHTML</b> is widely used, so we will focus on it.

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
&lt;b&gt;, &lt;i&gt; Boldface and italic  
&lt;pre&gt; Typically used for code: indented with a fixed-width font, spaces are significant (e.g., newlines are *preserved*)   
&lt;img&gt; Images  
&lt;a href="..."&gt; Hyperlink to another Web page  
&lt;!-- comments --&gt; Comment tags  
&lt;table&gt;, &lt;tr&gt;, &lt;td&gt;   Tables   
&lt;ul&gt;, &lt;li&gt;   Unordered list (with bullets)   
&lt;ol&gt;, &lt;li&gt;   Ordered list (numbered) 
&lt;div&gt; Used for *grouping related elements*, where the group occupies <b>entire lines</b> (forces a line break before and after)    
&lt;span&gt;  Used for *grouping related elements*, where the group is within a <b>single line</b> (no forced line breaks)   
&lt;form&gt;, &lt;input&gt;, &lt;textarea&gt;, &lt;select&gt;, ...  Used to create forms where users can input data   
&lt;title&gt;  Specify a title for the page, which will appear in the title bar for the browser window.  
&lt;link&gt;   Include CSS stylesheets &lt;script&gt; Used to add Javascript to a page (can be used in body as well)  

---

### Newer HTML - HTML5

* Additions tags to allow <b>content definition</b>
   &lt;article&gt;, &lt;section&gt;, &lt;header&gt;, &lt;footer&gt;, &lt;summary&gt;, &lt;aside&gt;, &lt;details&gt; 
  &lt;mark&gt;, &lt;figcaption&gt;, &lt;figure&gt;  
  &lt;nav&gt;, &lt;menuitem&gt; 
*  Drawing   
&nbsp;&nbsp; -  &lt;svg&gt;  Scalable Vector Graphics - Draw shapes  
&nbsp;&nbsp; -  &lt;canvas&gt; - Draw from JavaScript - 3D with WebGL   

* Timed media playback: &lt;video&gt; and &lt;audio&gt; 

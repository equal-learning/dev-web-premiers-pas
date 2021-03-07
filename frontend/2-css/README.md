
#&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Cascading Style Sheet    
###Driving problem behind CSS
What font type and size does <h1>Introduction</h1> generate?  
Answer: Some default from the browser (HTML tells what browser how)

Early HTML - Override defaults with attributes
````html
<table border="2" bordercolor="black">
````
    
Style sheets were added to address this:  
Specify style to use rather than browser default Not have to code styling on every element

###Key concept: Separate style from content  
<b>Content></b> (what to display) is in HTML files  
<b>Formatting</b> information (how to display it) is in separate style sheets (.css files). 
Use an element attribute named class to link (e.g. &lt;span class="test"&gt;) 
Result: define style information once, use in many places 
Consider can you make all the text in the app slightly bigger? Or purple is our new company color.  
DRY principle: Don't Repeat Yourself
 
 
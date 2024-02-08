HTML->

1. HTML stands for Hyper Text Markup Language
2. to use HTML for creating structure of website.
3. We called HTML as a markup language because it contains skeleton structure of the webpage.
4. All HTML re writeen in taglines.
5. h- heading, heading is a range from h1 to h6.
6. p- paragraph
7. br- line break <br>(single tag)
8. hr- horizontal line
9. img- insert image into the code, source,height width and alt are the attributes of the image
10. href - hyper reference to the another page or element
-self = own page, -blank = new page

HTML FORMATING->

<mark>= marked text
<b>= bold text
<i>= italic text
<em>= emphasized text
<ins>= inserted text
<del>= deletion text
<sub>= subscripted text
<sup>= superscripted text
HTML table gives us a table like structure where we can insert our data in row and column format.
<table>= main tag
<tr>= table row
<th>= table heading
<td>= table data

HTML list->

list are of two types;
1. unordered list - <ul>
2. ordered list - <ol>
<li>= list item

HTML block level element->

1. HTML contain 2 types of block level element to specify the structure of a web pages
    a. <p>= paragraph
    b. <div>= division

HTML forms->

1. HTML forms provides a form structure so that we can give our data by use of these forms
2. <input type = "text">
3. <input type = "password">
4. <input type = "submit">
5. <input type = "checkbox">
6. <input type = "radio-button">
7. <input type = "time">
8. <input type = "color">
9. <input type = "date">
10. <input type = "url">
11. <input type = "search">
12. <input type = "week">
13. <input type = "email">
14. <input type = "image">
15. <input type = "month">
16. <input type = "range">
17. <input type = "file">
18. <input type = "tel">
19. <input type = "number">

CSS->

1. Stands for Cascading Stylish Sheet.
2. We used css for designing and stylint the web pages.

Syntax->

h1             //Selector
{
    color:red    
}
3. Basically css are of 3 types
    a. inline css
    b. internal css
    c. extrenal css

Inline css->

<body>
<h1 style = "color:red">Today is Thursday</h1>
<p style = "backgroundcolor:yellow">Today we started css</p>
</body>

Internal css->

<head>
<style>
    h1
    { 
        color:red;
    }
    p{
        backgroundcolor:blue;
    }
</style>
</head>

External css->

1. It is a linkage to the outer css file to our main HTML element.

       index.HTML                                              style.CSS
    
<head>                                                      h1{ color:red; }
<link rel="stylesheet"href="style.css>
</head>
<body>
<h1>Today is a beautiful day</h1>
</body>

CSS Selector->

1. CSS selector are of 5 selector
    a. ID selector
    b. Class selector
    c. Universal selector
    d. Group selector
    e. Element selector
2. Selector means selecting a element which we have to designed 

ID selector->

1. ID selector are those selector which unique design/ we select only one element in HTML file.
2. it is denoted by '#'.
example:
<html>
<head>
<link rel = "stylesheet" href = "style.css">
</head>
<body>
<h1 id = "demo">Today is Thursday</h1>
<h1> we learn css</h1>
<h1>we write code....</h1>
</body>
</html>

style.css->
#demo{
    color:green;
}
h1{
    color:red;
}

class selector->

1. We used to class selector for repeating the simillar design in multiple times.
2. "." property we used to specify the class selector in our css file.

Universal selector->

1. We use universal selector to design whole html page in a single design.
2. "*" property we used to specify the class selector in our css file.


Group selector->

1. We used to group selector to create one design in which we have selected the tags.
2. Group selector we used by creating the group.

Element selector->

1. by selecting one single single element we have to design is called the elemnet selector.

practice->

1. Create a simple div with an id "box". add some text content inside the div. set it's background color
    to blue.
2. create 3 headings with h1, h2, h3 . give them all a class "heading" & set all color of "heading" to
    red.
3. create a button & set it's background color to 
    green using stylesheet.
    blue using <style> tag.
    pink using inline style.

VERSION CONTROL SYSTEM:-

1. git and github are those open source version control system.
2. we used version control system to store our code, share our code and collaborate our projects with each other.
3. example of vcs is:- git, github, gitlab,.....


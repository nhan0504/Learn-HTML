# HTML
## Doctype
- Define the type of the document
``` HTML
<!DOCTYPE html>
```

## Basic tags
``` HTML
<html>
    <head>
        <!-- What type of charater to display in the file -->
        <meta charset="UTF-8">
        <!-- Description of website -->
        <meta name="description" content="This is my website">
        <!-- Tile of website -->
        <title>My website</title>
    </head>
    <!-- Content of the website -->
    <body>
        <h1></h1> <!-- Header tag -->
        <p></p> <!-- paragraph tag -->
        <b></b> <!-- bold tag -->
        <i></i> <!-- italic tag --> 
        <br/> <!-- new line --> 
        <hr/> <!-- horizontal line -->  
        <big></big> <small></small> <!-- bigger or smaller text -->
        <sub></sub> <!-- subscript -->
        <sup></sup> <!-- superscript -->
    </body>
</html>
```

## Basic styling
``` HTML
<p style="color:blue; background-color: lightblue"></p>
```

## Page format
``` HTML
<body>
    <header>
        <nav></nav> <!-- navigational link,... -->
    
    </header>
    <main>

    </main>
    <footer>

    </footer>
</body>
```

## Linking
``` HTML
<!-- Link a website or image-->
<a href="https://www.google.com">Google</a>
<!-- Link a website that open in a newtab -->
<a href="https://www.google.com" target="_blank">Google</a>
```

## Image
``` HTMl
<!-- The text in alt will show if image cannot load -->
<img src="./img.jpg" alt="My image" />
<!-- Sizing image -->
<img width="100" height="100" src="./img.jpg" alt="My image" />
```

## Video
``` HTML
<!-- control attribute let you play the video-->
<video src="myVideo.mp4" poster="thumbnail.jpg" loop autoplay controls>
<!-- poster will show a thumbnail img for the video-->
<!-- autoplay the video-->
<!-- loop will replay the video when it ended -->
```

## List
### Unorder list
``` HTML
<ul>
    <li> item1 </li> <!-- list item tag -->
    <li> item2 </li>
</ul>
```
### Ordered list
``` HTML
<ol type="a"> <!-- list the item in a, b, c, ... order -->
    <li> item1 </li> 
    <li> item2 </li>
</ol>
```

## Table
``` HTML
<table>
    <thead> <!-- table head -->
        <caption> My table </caption> <!-- Name of the table -->
        <tr> <!-- table row -->
            <th>column1</th> <!-- table header -->
            <th>column2</th>
        </tr>
    </thead>
    <tbody> <!-- table body -->
        <tr> <!-- table row -->
            <td>data1</td> <!-- table data -->
            <td colspan="2">data2</td> <!-- data2 will take up 2 columns -->
        </tr>
    </tbody>
</table>    
```

## Div and span
``` HTML
<span></span> <!-- inline container -->
<div></div> <!-- block container -->
```

## User input data
``` HTML
<input type="text" value="Enter something"/> 
<!-- type specify what type of input-->
<!-- default value-->
<input type="password" />
<input type="date" />
<input type="file" />
<input type="checkbox" />
<input name = option type="radio" />
<input name = option type="radio" />
<textarea rows="10" cols="30"></textarea> <!-- A big area to enter text -->
```
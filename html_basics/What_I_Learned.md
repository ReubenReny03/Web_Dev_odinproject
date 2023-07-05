# HTML AnD CSS
## Tags
### Header tags
```
<h1> Heading 1 </h1>
<h2> Heading 2 </h2>
<h3> Heading 3 </h3>
<h4> Heading 4 </h4>
<h5> Heading 5 </h5>
<h6> Heading 6 </h6>
```
### Paragraph tags
```
<p> Write what you want </p>
```
### Some style tags
```
Bold --> <strong> or <b>
italic --> <em>   or <i>
```
### Comments
```
<!-- 
Write Comment here
-->
```

### Add Links
Example
```
<p>Git-Hub : <a href="https://github.com/ReubenReny03">ReubenReny03</a></p>
```
You can also link another html page
```
<p>Move to <a href="/html_basics/page_2.html"> page 2 CSS-Testing </a> </p>
```

### Add Images
Example
```
<img alt="ReMo Logo" src=" <link to image> ">
```
alt is used in case the image does not load it will show the alt message

### Internal CSS
code snippet for all basic css
```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" >
        <title>CSS Testing</title>
    </head>
    <body style="background-color: #1b1b1b; color: aliceblue;">
        <p>This is page 2 testing css <a style="color: blueviolet;">color to blue</a></p>
        <p style="font-size: 10px;"> making text smaller </p>
        <p style="font-size: 30px;">making text bigger</p>
        <p style="font-family: sans-serif;">font change</p>
    </body>
</html>
```

### External CSS
link the css to the html file 
```
<link rel="stylesheet" href="/css/page_3.css">
```
how to write css external file
```
body { #changes you want in the whole body tag
    background-color: #1b1b1b;
    color: aliceblue;
    font-size: 21px;
}
p { #changes you want in the p tag
    color: lightblue;
}
h1 { #changes you want in the h1 tag
    color: orange;
    font-size: 50px;
}
```
you can link it to any html page and it will take effect

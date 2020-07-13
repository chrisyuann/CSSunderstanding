# CSSunderstanding

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <div id="text">Hello, my name is Chris.<div>
    <script src="script.js"></script>
  </body>
</html>
    
#text {
  width: 190px;
  position: relative;
  top: 20px;
  left: 50px;

  transform: rotate(20deg);
  /* lets you rotate, scale, skew, or translate an element*/

  margin: 50px 0 0 70px;
  /*moves all edges of a box to another area: the top edge is the first edge that is moved, right edge is second edge, bottom edge is third edge, fourth edge is left edge*/

  border: 17px solid lightblue;
  border-radius: 10px 20px 20% 10pt;


  padding: 15px;
  /*inner space in a box*/
  
  background-color: lightcyan;
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

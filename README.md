<html>
  <head>
    <link href="style.css" rel="style.sheet" type= "text/css" />
  </head>
  <body>
    <h1> Hello </h1>
    <ul>
      <li> HeLlO </li>
      <li> HeLlO </li>
      <li> HeLlO </li>
      <li> HeLlO </li>
      <li> HeLlO </li>
    </ul>
    <p> Hello Test 123 </p>
    <p> 123 Test </p>
    <a href="#"> HELLO!! </a>
    <a href="#"> HELLO!! </a>
    <a href="#"> HELLO!! </a>
  </body>
</html>
body {
  font-family: 'Quicksand', sans-serif;
  background-color: #CCFFCC;
  color: #333333;
}
h1 {
  color: #58A6FF;
}
a {
  color: #333333;
  text-decoration: none;
}
a:hover {
color: #00796B;
}
ul > li {
  font-wheight: bold;
}
h1 + p {
  background-color: #00796B;
  padding: 10px;
  border-radius: 5px;
}
ul li:hover {
  color: #00796B;
}
ul li:nth-child(3) {
  color: #00796B;
}
p:not(:first-of-type) {
  text-decoration: overline;
}
p::first-letter {
  font-size: 200%;
  color: #00796B;
}

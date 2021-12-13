<html lang="en"><head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="week2.assingment.css">
</head>
<style>
	* {
  box-sizing: border-box;
  padding: 0;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

h1 {
  text-align: center;
}

div  {
  border: 1px solid black;
  background-color: gray;
  float: left;
  margin-right: 1em;
  margin-bottom: 1em;
}

@media (min-width: 992px) {
  div {
    width: 30%;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  .div1 {
    width: 47%;
  }
  .div2 {
    width: 47%;
  }
  .div3 {
    width: fit-content;
  }
}

@media (max-width: 767px) {
  div {
    width: fit-content;
  }
}

p {
  border: 1px solid black;
  padding: 10px;
  margin: auto;
  margin-left: max-content;
  float: right;
  padding-left: 3em;
  padding-right: 3em;
}

content {
  float: right;
  padding: 1em;
}

#p1 {
  background-color: rgb(194, 135, 145);
}

#p2 {
  background-color: rgb(155, 64, 64);
  color: aliceblue;
}

#p3 {
  background-color: rgb(247, 211, 164);
}

.section1 {
  background-color: aqua;
  width: 50%;
}

.section2 {
  background-color: brown;
  width: 50%;
}

</style>
<body>
  <h1>Our Menu</h1>
<div class="div1">
  <p id="p1">Chicken</p>
  <content>As part of the standards process, W3C requires that groups demonstrate implementation experience. W3C issues a call for implementations as part of standardization and welcomes public participation. See the list of specifications for which W3C is seeking implementation experience (called "Candidate Recommendations</content>
</div>
<div class="div2">
  <p id="p2">Beef</p>
  <content>As part of the standards process, W3C requires that groups demonstrate implementation experience. W3C issues a call for implementations as part of standardization and welcomes public participation. See the list of specifications for which W3C is seeking implementation experience (called "Candidate Recommendations</content>
</div>
<div class="div3">
  <p id="p3">Sushi</p>
  <content>As part of the standards process, W3C requires that groups demonstrate implementation experience. W3C issues a call for implementations as part of standardization and welcomes public participation. See the list of specifications for which W3C is seeking implementation experience (called "Candidate Recommendations</content>
</div>

</body></html>

## Welcome to WebClass

This is my code for the assignement in Module 2 in the Coursera course: HTML, CSS, and Javascript for Web Developers made by Yaakov Chaikin https://www.coursera.org/learn/html-css-javascript-for-web-developers

You can view and grade my code and if anything happen you can reach to me to help explain what I did.

Thanks a lot for taking the time to grade my code. Have a great day and happy coding!!!

This is my HTML file
### Markdown


```markdown
 <!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" type="text/css" href="css/style.css">
	<title>Assignment Solution for Module 2</title>
</head>
<body>
	<h1>Our Menu</h1>
	<div class="container">
		<div class="column col-lg-4 col-md-6 col-sm-12">
			<div class="section-title section-title-red">Chicken</div>
			<section>
				Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
				tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
				quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
				consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
				cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
				proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
			</section>
		</div>

		<div class="column col-lg-4 col-md-6 col-sm-12">
			<div class="section-title section-title-green">Beef</div>
			<section>
				Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
				tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
				quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
				consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
				cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
				proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
			</section>
		</div>

		<div class="column col-lg-4 col-md-last col-sm-12">
			<div class="section-title section-title-blue">Suchi</div>
			<section>
				Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
				tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
				quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
				consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
				cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
				proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
			</section>
		</div>
	</div>
</body>
</html>
 
 ```
 
 and this is my CSS style file
 ```markdown
 *{
	box-sizing: border-box;
}

html, body{
	margin: 0;
	padding: 0;
	width:100%;
  	font-family: Helviteca, sans-serif;
}

h1{
	text-align: center;
	font-size: 175%;
	margin: 50px 0px;
}

.container{
	width: 100%;
}

.column{
	position: relative;
}

section{
	padding: 30px 10px 10px 10px;
	margin: 0px 0px 30px 30px;
	background-color: #ecf0f1;
	border: 1px solid black;
}

.section-title{
	border: 1px solid black;
	width: 150px;
	height: 25px;
	background-color: black;
	position: absolute;
	top: 0px;
	right: 0px;
	text-align: center;
	font-size: 125%;
	color: white;
}

.section-title-red{
	background-color: #c0392b;
}

.section-title-green{
	background-color: #16a085;
}

.section-title-blue{
	background-color: #2980b9;
}

/********** Desktop Version **********/
@media (min-width: 992px) {
  .col-lg-4 {
    float: left;
    width: 32.5%;
  }
}

/********** Tablet Version **********/
@media (min-width: 768px) and (max-width: 991px) {
  .col-md-6 {
    float: left;
    width: 48%;
  }

  .col-md-last {
  	float: left;
    width: 96%;
  }
}

/********** Mobile Version **********/
@media (max-width: 767px) {
  .col-sm-12 {
    float: left;
    width: 94%;
  }

  h1{
  	margin: 30px 0px;
  }
}
 
 ```

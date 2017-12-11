# ytark2.github.io
<!DOCTYPE html>
<html>
<head>
    <title>My Personal Webpage</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
</head>
<body>
<div id="wrapper">
    
	<div id="header">
		<div id="nav"><a href="index.html">Home</a> | <a href="#">About Me</a> | <a href="#">Contact Me</a> | <a href="#">My Photos</a> | <a href="#">My Videos</a></div>
		<div id="bg"></div>
	</div>
	
	<div id="main-content">
		<div id="left-column">
			<div id="logo">
			Welcome to Michael Scott's Webpage
			</div>
			<div class="box">
        		<h1>What You'll Find Here</h1>
        		<p>This is my space. Here are some of my interests: </p>
				<ul style="margin-top:10px;">
					<li>Saying "That's what she said"</li>
					<li>Writing song parodies</li>
					<li>Playing ice hockey</li>
					<li>Wearing jeans</li>
					<li>Chrysler cars</li>
				</ul>
			</div>
			<h2>A Few of My Famous Quotes</h2>
			<p>
				<img src="http://img189.imageshack.us/img189/9177/paperru.jpg
" width="139" height="150" style="margin: 0 10px 10px 0;float:left;" />
				<em>"That's what she said."</em> - Me<br/>
				<em>"Would I rather be feared or loved? Easy, both. I want people to be afraid of how much they love me."</em> - Me<br/>
				<em>"Wikipedia is the best thing ever. Anyone in the world can write anything they want about any subject, so you know you are getting the best possible information."</em> - Me<br/>
				<em>"I am Michael, and I am part English, Irish, German, and Scottish, sort of a virtual United Nations."</em> - Me<br/>
			</p>
		</div>
		<div id="right-column">
			<div id="main-image"><img src="http://img38.imageshack.us/img38/7065/michaelscotto.jpg
" width="160" height="188" /></div>
			<div class="sidebar">
				<h3>Blurb About Me</h3>
				<p>My name is Michael Scott. And I love Dunder Mifflin and Dwight Schrute.</p>
				<h3>Find Me Elsewhere</h3>
				<div class="box">
					<ul>
						<li><a href="http://facebook.com" target="_blank">Facebook</a></li>
						<li><a href="http://twitter.com" target="_blank">Twitter</a></li>
						<li><a href="http://linkedin.com" target="_blank">LinkedIn</a></li>
						<li><a href="http://tumblr.com" target="_blank">Tumblr</a></li>
						<li><a href="http://pinterest.com" target="_blank">Pinterest </a></li>
					</ul>
				</div>
			</div>
		</div>
	</div>
	<div id="footer">
		Copyright &copy; 2012 Michael Scott. All rights reserved.<br/>
		Layout adapted from <a href="http://www.web-designers-directory.org/" target="_blank">Web Designers' Directory</a>.
	</div>
</div>

</body>


/* Layout */

body {
    font:normal 12px/1.6em Arial, Helvetica, sans-serif;
	color:#2a3845;
	margin:0;
	padding:0;
	background:#FFFFFF;
}

p {
	margin:0;
	padding:0;
}

#wrapper {
	margin:0 auto;
	width:632px;
	border-left:1px solid #f0e9eb;
	border-right:1px solid #f0e9eb;
}

#header {
	margin:0 1px;
}

#bg {
	height:36px;
	background:url('http://img840.imageshack.us/img840/9886/87926428.gif') repeat-x;
}

#main-content {
	margin:0 auto;
}

#main-image {
	text-align:center;
}

#left-column {
	width:300px;
	padding:0 30px 30px;
	float:left;
}

#right-column {
	width:270px;
	float:right;
}

.sidebar {
	width:218px;
	margin:0 auto;
	padding:10px 25px;
	background:url('http://img404.imageshack.us/img404/3092/shadowh.jpg') no-repeat top;
}

#footer {
	background:#f7f7f7;
	border-top:1px solid #f0e9eb;
	padding:10px 15px;
	clear:both;
}

/* Global Styling */

a:visited, a:link {
	color:#a43b55;
	text-decoration:underline;
	background:none;
}

a:hover {
	color:#a43b55;
	text-decoration:none;
	background:none;
}

h1 {
	color:#7a2e40;
	margin:0 0 10px;
	padding-bottom:10px;
	font:normal 17px Georgia, serif;
	border-bottom:1px solid #efece7;
}

h2 {
	color:#7a2e40;
	margin:20px 0 10px;
	padding-bottom:10px;
	font:normal 17px Georgia, serif;
	border-bottom:1px solid #efece7;
}

h3 {
	color:#7a2e40;
	margin:10px 0;
	padding-bottom:10px;
	font:bold 14px Arial, Helvetica, sans-serif;
	border-bottom:1px solid #efece7;
}

ul {
	padding:0;
	margin:0 0 0 17px;
	list-style:square url('http://img525.imageshack.us/img525/1890/bulletr.gif');
}

.box {
	background:#f7f7f7;
	border:1px solid #f0e9eb;
	padding:15px;
}

#nav {
	background:#06a;
	padding:10px 20px;
	text-align:right;
	color:#f6dde3;
}

#nav a {
	margin: 0 10px;
}

#nav a:visited, #nav a:link {
	text-decoration:none;
	color:#f6dde3;
}

#nav a:hover {
	text-decoration:underline;
	color:#f6dde3;
}

#logo {
	margin-bottom:20px;
	font:normal 18px Georgia, serif;
	color:#fa7393;
}
</html>

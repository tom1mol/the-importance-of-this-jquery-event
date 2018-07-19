traversing up and down the DOM
 
 <!doctype html>
-<html>
+<html lang="en">
 <head>
 	<meta charset="utf-8" />
 	<meta name="viewport" content="width=device-width, initial-scale=1">
 	<title>jQuery Traversing Mt Dom</title>
 	<link href="css/style.css" rel="stylesheet">
 	<link href='https://fonts.googleapis.com/css?family=Roboto' rel='stylesheet'>
 	<link href='https://fonts.googleapis.com/css?family=Dosis' rel='stylesheet'>
 </head>
 <body>
 	<div id="container">
 		<nav>
 			<ul>
 				<li id="logoNav">CODE INSTITUTE</li>
 				<li id="stream1_btn">Stream 1</li>
 				<li id="stream2_btn">Stream 2</li>
 				<li id="stream3_btn">Stream 3</li>
 			</ul>
 		</nav>
 		<div class="card stream1">
 			<img class="card_image" src="images/3.png" alt="code icon">
 			<div class="card_bottom">
 				<h2 class="card_head">HTML</h2>
 				<p class="card_para">Once you join a <a href="#">Code Institute</a> Bootcamp you will be taken on an accelerated <a href="#">contextualised</a>	 learning path across 3 streams. Nothing is learned in isolation.We contextualise the content so that the knowledge and skills gained in each learning unit feeds into, and is <a href="#">expanded</a> upon, within the next unit.The outputs of each stream will be a project. </p>
 				<button class="bottom_button">Button</button>
 			</div>
 		</div>
 		<div class="card stream3">
 			<img class="card_image" src="images/1.png" alt="code icon">	
 			<h2 class="card_head">MySql</h2>
 			<p class="card_para">If you have questions about your <a href="#">career</a> in coding or simply want to meet the Code Institute team, then come along to our next Careers Open Evening in Dublin</p>
 			<button class="bottom_button">Button</button>
 		</div>
 		
 		<div class="card stream2">
 			<img class="card_image" src="images/2.png" alt="code icon">
 			<h2 class="card_head">Python</h2>
 			<p class="card_para">If you have <a href="#">questions</a> about your career in coding or simply want to meet the  Code Institute team, then come along to our next <a href="#">Careers</a> Open Evening in Dublin</p>
 			<button class="bottom_button">Button</button>
 		</div>
 		<div class="card stream1">
 			<img class="card_image" src="images/3.png" alt="code icon">
 			<div class="card_bottom">
 				<h2 class="card_head">jQuery</h2>
 				<p class="card_para">Once you join a Code Institute Bootcamp you will be taken on an accelerated contextualised learning path across 3 <a href="#">streams</a>. Nothing is learned in isolation.We contextualise the content so that the knowledge and skills gained in each <a href="#">learning</a> unit feeds into, and is expanded upon, within the next unit.The outputs of each stream will be a project. </p>
 				<button class="bottom_button">Button</button>
 			</div>
 		</div>
 		<div class="card stream3">
 			<img class="card_image" src="images/4.png" alt="code icon">
 			<h2 class="card_head">Django</h2>
 			<p class="card_para">The syllabus has been developed to help you transform your career. The summarised syllabus, below, provides you with a <a href="#">snapshop</a> of what skills you will come away with. Feel free to contact us for more detail on what you will learn.</p>
 			<button class="bottom_button">Button</button>
 		</div>
 		<div class="card stream1">
 			<img class="card_image" src="images/1.png" alt="code icon">
 			<h2 class="card_head">CSS</h2>
 			<p class="card_para">The <a href="#">syllabus</a> has been developed to help you transform your career. The summarised syllabus, below, provides you with a snapshop of what skills you will come away with. Feel free to contact us for more detail on what you will learn.</p>
 			<button class="bottom_button">Button</button>
 		</div>
 		<div id="my_footer">
 			<p id="copyright">Copyright Infomation</p>
 		</div>
 	</div>
 	<script
 	src="https://code.jquery.com/jquery-3.2.1.js"
 	integrity="sha256-DZAnKJ/6XZ9si04Hgrsxu/8s717jcIzLy3oi35EouyE="
 	crossorigin="anonymous"></script>
 	<script src="js/script.js"></script> <!-- Scripts located at the bottom of the body to insure page is fully loaded before execution -->
 	
 </body>
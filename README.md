# front-web-development

<!DOCTYPE html>
<!DOCTYPE html>
<html>
<head>
	<title>WE HAVE IT ALL</title>
	<link rel="stylesheet"  type = "text/css" href="maincss.css">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
	<link href="https://fonts.googleapis.com/css?family=Righteous" rel="stylesheet">
	<script src="R:\web development\my work\WE_HAVE_IT_ALL\jquery.js"></script>
	<script>
		
		$(document).ready(function(){
		trans = $("h1");
		trans1 = $(".srch_form");
		trans2 = $("#nav > li:first");
		trans3 = $("#login");
		trans4 = $("#container1");
		trans5 = $("#sepa_line");
		trans6 = $("#nav > li:last");
		trans7 = $("#signup");
		trans8 = $(".log_cut");
		trans9 = $(".srch-button");
		trans10 =$("#list_container");
		trans11 =$("#list_content");
		trans12 =$("footer");
		trans13 =$("header");
		trans16 = $(".search");
		trans17 = $("#logo");
		trans8.click(function(){
			trans7.css({
						"top":"-150%","transition-property":"all",
						"transition-duration":"1s",
						"transition-timing-function":"cubic-bezier(0.5, -.8, .3, 1.5)"});
			trans3.css({"left":"-30%","transition-property":"all",
							"transition-duration":"1s",
							"transition-timing-function":"cubic-bezier(0.5, -.8, .3, 1.5)"});
			trans4.css({
						 "left":"30%", "transition-property":"all","transition-duration":"1s",
					"transition-timing-function":"cubic-bezier(0.5, 0, .3, 1.5)"});
			trans5.css({"display":"none", "height":"10%", "top":"45%",});
				});
		trans.mouseover(function(){
		trans.css({
			"text-shadow":"0px 2px 1px rgba(0,0,0,0.5)", "font-size": "1em", 
	        "transition-property": "text-shadow, font-size", "transition-duration":"0.3s , 0.5s",
			 "transition-delay": "0.3s, 0s"
				});
		trans1.css({"width":"100%","visibility":"visible","transition-property":"width, visibility","transition-timing-function":"linear","transition-duration":"0.5s,0s"});
			});
		trans.mouseout(function(){
			trans.css({
			"text-shadow":"0px 0px 0px #000000", "font-size":"2em", 
	        "transition-property": "text-shadow, font-size", "transition-duration":"0.5s , 1s",
	       	"transition-duration": "0.5s , 1s", "transition-delay": "3s, 3s"
	       		});
		});
		trans1.mouseout(function(){

			trans1.css({"visibility":"hidden", "transition-duration":"10s"});
		});



		trans2.click(function(){
			trans10.css({"visibility":"hidden","box-shadow":" 0px 5px 10px 1px","transition":"box-shadow 1s linear"
						});
			trans4.css({"position":"relative", "top":"15%", "transition":"top 2s ease","display":"block"});
					trans7.css({
						"top":"-150%","transition-property":"all",
						"transition-duration":"1s",
						"transition-timing-function":"cubic-bezier(0.5, -.8, .3, 1.5)"});

				trans3.css({"left":"8%","transition-property":"all",
							"transition-duration":"1s",
							"transition-timing-function":"cubic-bezier(0.5, -.8, .3, 1.5)"});
				trans4.css({
						 "left":"55%", "transition-property":"all","transition-duration":"1s",
					"transition-timing-function":"cubic-bezier(0.5, 0, .3, 1.5)"});
				trans5.css({"display":"block", "height":"70%", "top":"15%","left":"50%", 
							"transition-duration":"0.5s",
							"transition-timing-function":"ease-end"});
			});

		trans6.click(function(){
			trans10.css({"visibility":"hidden","box-shadow":" 0px 5px 10px 1px","transition":"box-shadow 1s linear"
						});
			trans4.css({"position":"relative", "top":"15%", "transition":"top 2s ease","display":"block"});
				trans3.css({"left":"-30%","transition-property":"all",
							"transition-duration":"1s",
							"transition-timing-function":"cubic-bezier(0.5, -.8, .3, 1.5)"});
				trans4.css({
						 "left":"5%", "transition-property":"all","transition-duration":"1s",
						 "transition-timing-function":"cubic-bezier(0.5, 0, .3, 1.5)"});
				trans7.css({
						"top":"10%","transition-property":"all",
						"transition-duration":"1s",
						"transition-timing-function":"cubic-bezier(0.5, -.8, .3, 1.5)"});

				trans5.css({"display":"block", "height":"70%", "top":"15%","left":"50%", 
							"transition-duration":"0.5s",
							"transition-timing-function":"ease-out"});
			});
		trans9.click(function(){
			trans10.css({"visibility":"visible","box-shadow":" 0px 5px 10px 1px","transition":"box-shadow 1s linear"
						});
			trans4.css({"position":"absolute", "top":"-150%", "transition":"top 2s ease"});
			trans11.css({"display":"block"});
			trans12.css({"top":"30%"});
			trans13.css({"position":"fixed", "z-index":"20","box-shadow":"0px 2px 20px 2px","transition":"box-shadow 1s linear"});
			$("section").css({"top":"130px"});
			$("footer").css({"top":"160px"});

			var name = trans16.val();
				$(".srchd").text(name);
					});
		$("#list_close").click(function(){
			trans11.css({"display":"block"});
			trans10.css({"visibility":"hidden"});
			trans4.css({"top":"-10%","transition":"top 1s ease"});
			trans13.css({"position":"fixed", "z-index":"10","box-shadow":"0px 0px 0px 0px"});

		});
		trans17.mouseover(function() {

			trans17.css({"transform":"rotate(0.5turn)", "transition-duration":"1s"});
		});
		trans17.mouseout(function() {
			trans17.css({"transform":"rotate(0turn)"});
		});
		});
		
	</script>
</head>
<body>
	<header id = "header">
	<img  id="logo" src="R:\\web development\\my work\\WE_HAVE_IT_ALL\\images\\Group 1.svg">
			<ul id="nav">
				<li>Login</li>
				<li>Sign Up</li>
			</ul>
		
	</header>

	<section id = "section">
		<div id="login" class="login">
			<button class="log_cut"><i class="fa fa-close"></i></button>
			<center><h3 style=" margin:2% 0% 0% 0%;">Login</h3></center>
			<form id="log_for">
			<input type="text" name="user" placeholder="User_id">
			<input type="password" name="password" placeholder="Password">
			</form>
			<button style="background: transparent; border:0; font-size: 1.5em; position: relative; left: 40%; top:-20%;"><i class="fa fa-arrow-right"></i></button>

			<ul class="login_nav">
			<li><i class="fa fa-instagram" style="font-size:1em;"></i></li>
			<li><i class="fa fa-facebook" style="font-size:1em;"></i></li>
			<li><i class="fa fa-github" style="font-size:1em;"></i></li>
			
		</ul>
		</div>

			<div id="signup" >
				<button class="log_cut"><i class="fa fa-close"></i></button>
			<center><h3 style=" margin:2% 0% 0% 0%;">Login</h3></center>
			<form id="log_for">
			<input type="text" name="user" placeholder="E-mail">
			<input type="password" name="password" placeholder="Choose a Password">
			<input type="password" name="password" placeholder="Retype Password"></form>
			<button style="background: transparent; border:0; font-size: 1.5em; position: relative; left: 40%; top:-20%;"><i class="fa fa-arrow-right"></i></button>
			<ul class="login_nav">
			<li><i class="fa fa-instagram" style="font-size:1em;"></i></li>
			<li><i class="fa fa-facebook" style="font-size:1em;"></i></li>
			<li><i class="fa fa-github" style="font-size:1em;"></i></li>
			
		</ul>
		</div>
		

		<hr id="sepa_line">

		<div id = "container1">
			<center id=" center"><h1 id = "heading1" class="we_have"> We Have It All!</h1>
			<div class="srch_form">
				<input  class="search" type="text" name="search" placeholder="SEARCH">
				<button  id = "srch-button" class="srch-button"><i class="fa fa-search" style="font-size:1;"></i></button>
			</div></center>

		</div>
		<div id="list_container">
			<p id=list_head >
				<button class="list_head_ele" id="list_close"><i class="fa fa-close"></i></button>
				<span class="srchd"></span>
				<input class="list_head_ele" type="text" name="search">
				<button class="list_head_ele"><i class="fa fa-search "></i></button>
			</p>
			<p id="list_content">
			</p>
		</div>
	</section>

<footer>
	<ul id="more">
			<li><a href="R:\web development\my work\WE_HAVE_IT_ALL\feedbackpage.html">Feedback</a> <i class="	fa fa-address-card" style="font-size:1.5em;"></i></li>	
			<li>About <i class="fa fa-child" style="font-size:1.5em;"></i></li>	
			<li>Contact us <i class="fa fa-wechat" style="font-size:1.5em;"></i></li>	
	</ul>
	
	<p id = "copy_right"> 
		&copy; Rajan kumar
		</p>
	<ul id = "follow-nav">
		<li style =" display: block; text-decoration: none; margin-bottom: 5%; ">Follow us on..!   </li>
		<li><i class="fa fa-instagram" style="font-size:1.5em;"></i></li>
		<li><i class="fa fa-facebook" style="font-size:1.5em;"></i></li>
		<li><i class="fa fa-github" style="font-size:1.5em;"></i></li>
		<li></li>
		<li><i class="fa fa-google-plus-square" style="font-size:1.5em;"></i></li>
		
	</ul>
</footer>
				


</body>
</html>

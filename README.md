<!doctype html>
<html lang="en">
<title>damix44</title>
<head>
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
    <script src="typed.js" type="text/javascript"></script>


    <script>
    $(function(){
        $("#typed").typed({
            strings: [
            "READY",
"Hi, my name is Damian Ambrozek. I live in Radom, PL. <br>I love programming in one of my favourite languages:<br>"+
"<br>  -> C"+
"<br>  -> C++"+
"<br>  -> Python"+
"<br>  -> Javascript"+
"<br><br>Please check my GitHub page below for some of my projects<br><br>\><a href=\"https:\/\/github.com\/radx64\">GitHub</a>\< <br>"
            ],
            typeSpeed: 50,
            backDelay: 100,
            startDelay: 1500,
            loop: false,
            cursorChar: "&#9608;",
            contentType: 'html', // or text
            // defaults to false for infinite loop
            loopCount: false,
            callback: function(){ foo(); },
            resetCallback: function() { newTyped(); }
        })
        $(".reset").click(function(){
            $("#typed").typed('reset');
        });
    });
    function newTyped(){ /* A new typed object */ }
    function foo(){}
    </script>
 <link href="console.css" rel="stylesheet"/>
</head>
<body>
<div class="css-typing">
	<a> damix44.github.io </a><br>
	<a> ================ </a><br>
	<div class="wrap">
		<span id="typed" style="white-space:pre;"></span>
	</div>
	<div class="links">
	<br>
	<br>
	
</div>


</body>

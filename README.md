<!--My first real attempt at a non-interactive webpage from scratch in a text editor.  Some url links and img srcs had to be changed to share it on codecademy, but overall the layout remained the same.  Looking back on this now I can see a lot of redundant code in css that could be shortened quite a bit, but I'll keep it as is to show my progress as time goes on.-->

<!DOCTYPE html>
<html>
	<head>
	    <!--Title in tab of browser-->
		<title>Learning Images and Backgrounds!</title>
		<!--Linking to css.stylesheet in codecademy-->
		<link rel="stylesheet" href="style.css">
		<!--Linking googlefonts resource-->
		<link href="https://fonts.googleapis.com/css?family=Metal+Mania" rel="stylesheet">
	</head>

	<body>
		<div class="header">
			<h1>Almighty Skeletor<h1>
		</div>   
        <!--The idea here was to wrap the maincontent and navbar in a div, to then draw a border in css.-->
		<div class="mainborder">
				<div class="navbar">
					<ul>
					    <!--I removed the url links in the navbar because they don't work in codecademy-->
						<li><a href="">Home</a></li>
						<li> | </li>
						<li><a href="">About Skeletor</a></li>
						<li> | </li>
						<li><a href="">Our Enemy</a></li>
						<li> | </li>
						<li><a href="">Contact Skeletor, Myaa!</a></li>
					</ul>
				</div>
			<div class="maincontent">
				<div id="episode1">
					<h3 id="episode1header">Episode 1. "The Cosmic Comet"</h3>
					<img id="img_1" src="https://images-na.ssl-images-amazon.com/images/M/MV5BMTQ5ODU5MDQ1Nl5BMl5BanBnXkFtZTcwMTUwNDk4OA@@._V1_.jpg">
					<p id="para1">A comet has turned evil and is working for Skeletor. He-Man must convince an old wizard named Zagraz with power over comets to help save Eternia. Man-at-Arms tells viewers they'll all make mistakes, but to "try, try again" and remain confident.</p>
				</div>

				<div id="episode2">
					<h3 id="episode2header">Episode 2. "The Shaping Staff"</h3>
					<img id="img_2" src="https://images-na.ssl-images-amazon.com/images/M/MV5BMjI0ODgyOTYxNF5BMl5BanBnXkFtZTcwMjUwNDk4OA@@._V1_.jpg">
					<p id="para2">Evil-Lyn has gained hold of the magical Shaping Staff, which can transform anyone at whom the holder aims it. Orko tells viewers some strangers are dangerous, so never accept gifts from or talk to any.</p>
				</div>

				<div id="episode3">
					<h3 id="episode3header">Episode 3. "Disappearing Act"</h3>
					<img id="img_3" src="https://images-na.ssl-images-amazon.com/images/M/MV5BZjE5MzBjZDMtOWM4NC00MTZiLWEzNDgtYmU3YzljMzk4YzVhXkEyXkFqcGdeQXVyMjM4Mzg1OTk@._V1_.jpg">
					<p id="para3">Orko's magic wand accidentally hits Prince Adam's sword and made it go to the past. Skeletor captures Prince Adam and waits for He-Man to come to his rescue. Man-at-Arms tells viewers He-Man's brain helped more than his muscles in that problem, and that brains can and should be exercised.</p>
				</div>

				<div id="episode4">
					<h3 id="episode4header">Episode 4. "Diamond Ray of Disappearance"</h3>
					<img id="img_4" src="https://images-na.ssl-images-amazon.com/images/M/MV5BMDc1MGQ2OWYtNjliNC00NjMzLWI1MzQtNjIxODRmNDgxYzZlXkEyXkFqcGdeQXVyMjM4Mzg1OTk@._V1_.jpg">
					<p id="para4">Skeletor wreaks havoc at the Royal Palace with the Diamond of Disappearance, which transports all who look at it into a timeless dimension. Beast Man, Mer-Man, Trap Jaw, Tri-Klops, Evil-Lyn and Panthor appear. He-Man tells viewers to watch out for those people who promise a quick way to riches and to "not sell yourself short."</p>
				</div>

				<div id="episode5">
					<h3 id="episode5header">Episode 5. "She-Demon of Phantos"</h3>
					<img id="img_5" src="https://images-na.ssl-images-amazon.com/images/M/MV5BOTU5ZGI1MzItNjc2YS00MDhmLThhNmItZjI3NGE3YzI1NDRjXkEyXkFqcGdeQXVyMjM4Mzg1OTk@._V1_.jpg">
					<p id="para5">Skeletor has taken control of Queen Elmora, ruler of the moon of Phantos, and is forcing her to supply him with a powerful metal called Photanium. He-Man tells viewers to be cautious, whether or not a public safety official is around.</p>
			</div>
		</div>
	</body>
</html>

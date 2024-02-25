# WorldSoccer

<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Home</title>
 <link rel="icon" type="image/x-icon" href="images/image6.png/favicon.ico">

<link rel="stylesheet" href="project_style.css">
<script type = "text/javascript">
<!--
//displays the webpage's last modification date and time
//document.write('Page last modified: ',document.lastModified.toLocaleString());


//variable to save user's name
var username = localStorage.getItem("username");

//if user is not save, then prompt user for the following..
if(!username){

	//prompt user to enter their name
    username = prompt("Please enter username");
    localStorage.setItem("username", username);
}


-->
</script>
</head>

<body>


<!-- the very top of each page -->
<div id="banner">
	<img class="right" src="images/image6.png" alt="nav soccer ball" width="165" height="95">
	
	<h1><br>W<img src="images/image3.png" alt="world soccer ball" width="35" height="27">RLD SOCCER</h1>
	
	
	</div>


<!-- website navigation bar -->
 <nav>
		<ul>
		  <li><a href="home.html">Home</a></li>
		  <li><a href="news.html">News</a></li>
		  <li><a href="highlights.html">Highlights</a></li>
		  <li><a href="quiz.html">Quiz</a></li>
		  <li><a href="records.html">other</a></li>
		  <li><a href="cite.html">References</a></li>
		</ul>
</nav>


<!-- content div displays all the main content of each webpage -->
<div id="content">
	<h2>Richarlison's future at Spurs</h2><img  src="images/image7.jpg" alt="Richarlison" width="275" height="150">
	<p>Los Blancos boss Carlo Ancelotti knows Brazil international <a href="https://www.espn.com/soccer/blog-transfer-talk/story/4879499/transfer-talk-tottenham-star-richarlison-remains-on-real-madrids-radar">
	Richarlison </a>well from his time in charge of Everton, while Madrid officials 
	believe Spurs could be willing to raise funds for new players by offloading the 24-year-old in the summer.
	Richarlison was a big-money signing by Tottenham in the summer of 2022, but he has only started five league games and is yet to score a league 
	goal for the club this season. His record for Brazil is better, though; he averaged a goal every 43 minutes in 2022 for his national side.
	</p>


<!-- a three column table displaying details of upcoming soccer games-->
	<h2> Upcoming games <a href id="jump"> <img src="images/image4.png" alt="soccer kick" width="45" height="33"></a></h2>
<table id="tables">
  <tr>
    <th>Date</th>
    <th>Team</th>
    <th>League</th>
	
  </tr>
  <tr>
    <td>2:45 PM<br>Tomorrow</td>
    <td>RB Leipzig <i>vs</i> Manchester City</td>
    <td>Champions League<br>Round of 16</td>
  </tr>
  <tr>
    <td>3:00 PM<br>Tomorrow</td>
    <td>Inter Milan <i>vs</i> FC Porto</td>
    <td>Champions League<br>Round of 16</td>
  </tr>
  <tr>
    <td>3:00 PM<br>Friday</td>
    <td>Manchester United <i>vs</i> Barcelona</td>
    <td>Europa League<br>Knockout rounds</td>
  </tr>
  <tr>
    <td>11:30 AM<br>Saturday</td>
    <td>Fulham <i>vs</i> Wolves</td>
    <td>English Premier League<br>Week 24</td>
  </tr>
    <tr>
    <td>9:30 AM<br>Saturday</td>
    <td>Leicester City <i>vs</i> Arsenal</td>
    <td>English Premier League<br>Week 24</td>
  </tr>
  
  
	</table><br>
	

	
<!-- sign up form for users to fill in -->
	<h3>Sign up for weekly news and highlight updates from us!</h3>
	<form action="/action_page.php">
	  Name: <input type="text" id="fname" name="fname" value=""><br>
	  Email: <input type="text" id="lname" name="lname" value="JohnDoe@gmail.com"><br>
	  Age: <input type="date" id="age" name="age" value=""><br>
	  Favorite Team: <input type="text" id="name" name="name" value=""><br>
	  Which league/s do you follow?<br>
	  
	 <input type="checkbox" id="team1" name="Premier league" value="Bike">
		<label>Premier league</label><br>
	
	<input type="checkbox" id="team2" name="La Liga" value="Bike">
		<label>La Liga</label><br>
	
	<input type="checkbox" id="team3" name="Bundesliga" value="Bike">
		<label>Bundesliga</label><br>
	
	<input type="checkbox" id="team4" name="Ligue 1" value="Bike">
		<label>Ligue 1</label><br>
			  
	<input type="checkbox" id="team5" name="Champions league" value="Bike">
		<label>Champions league</label><br>
			  
	<input type="checkbox" id="team6" name="Europa league" value="Bike">
		<label>Europa league</label><br>
	  
	<input type="submit" value="Submit"><br>
	</form><br>
	
	
	
<!-- Gives information about the website -->
	<h3>About Us</h3>
	<p>We are soccer fanatics who love to share the love for the sport to the world. We are W<img src="images/image3.png" alt="world soccer ball" width="15" height="10">RLD SOCCER! 
	Our team works hard to keep our fans and followers updated, with our top <a href="project_style.css">  web designers</a> and researchers working hard 
	to give you, the best fans, more about the <i>beautiful game</i>. In our site, we provide <a href="news.html">latest news</a>, <a href="highlights.html">
	highlights</a> of recent games, goals throughout different popular leagues, and <a href ="#jump">upcoming soccer games</a>  and goals of recent games
	</p>

	
<!-- footer -->
 </div>
<div id="footer">
	<p>This website is developed as an educational project. Certain materials are included under the fair use exemption of the U.S. Copyright Law and have been 
		prepared according to the multimedia fair use guidelines and are restricted from further use.</p>
</div>


</body>
</html>

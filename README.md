# remember_me
HTML file 
//
//
//
//

<!DOCTYPE html>

<html>

<head>
    <title>
        Thy Game
    </title>
    <link rel="stylesheet" href="stylesheet.css">
    
    <script type="text/javascript" src="script.js"></script>

</head>

<body onload="rest(1)" class="body">
    <!--<embed name="lostmojo" src="Brambles - To Speak of Solitude.mp3" loop="true" hidden="true" autostart="true">-->
    <header class="mainheader">
        <h1> Remember Me! </h1>
        <nav>
            <ul>
                <li class="active" onclick="rest(1)"><a href="#">Level 1</a></li>
                <li><a href="#" onclick="rest(2)">Level 2</a></li>
                <li><a href="#" onclick="rest(3)">Level 3</a></li>
                <li><a href="#" onclick="rest(4)">Level 4 </a></li>
                <li><a href="#" onclick="rest(1)">Restart</a></li>
            </ul>
        </nav>
    </header>
    <div id="animation" style="margin-bottom: -20px;">

    </div>
 
    <div id="wrapper">


    </div>
    
    <div id="bottomWrapper">
        <p id="counter"></p>
        <p>
            Rules:<br>
            <ol type="1">
                <li>You have to match the pictures which are hidden in boxes.</li>
                <li>For each match you will be given 1 point.</li>
                <li>Wrong match would score you down by 0.25 points.</li>
                <li>Keep trying until you score <span id="textId"></span> points in your first try.</li>
                <li>Your score would be added in each game.</li>
            </ol>

    </div>
    
    <div class="mainfooter">
        <span id="span1">
            Follow us on:
            <a href="https://www.facebook.com/" target="_blank">
                <img src="http://static.viewbook.com/images/social_icons/facebook_32.png" />
            </a>
            <a href="https://twitter.com/" target="_blank">
                <img src="http://static.viewbook.com/images/social_icons/twitter_32.png" />
            </a>

            <a href="https://www.google.co.in/?gws_rd=ssl" target="_blank">
                <img src="http://static.viewbook.com/images/social_icons/google_32.png" />
            </a>
        </span>

    </div>


</body>
</html>

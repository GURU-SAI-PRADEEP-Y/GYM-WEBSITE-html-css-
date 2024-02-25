# GYM-WEBSITE-html-css-
This is my first repository for web development - front end.
This is having only html and css part...

# HTML FILE....

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title style="position: relative";color="white">Gym rats</title>
    <link rel="stylesheet" href="web1.css">
    <link rel="icon" type="image" href="barbell.png">
</head>
<body>
    <div class = "zero">
        <nav>
            <h2 class="logo"><strong>Lia</strong><span> <strong>Heights</strong></span></h2>
             <ul>
                <li><a href="#">Home</a></li>
                <li><a href="About Us.html">About Us</a></li>
                <li><a href="#">Service</a></li>
                <li><a href="con us.html">contact us</a></li>
             </ul>
             <button type="button">Sign In</button>
             <button type="button">Sign Up</button>
        </nav>
    </div>
    <h1 style= color:white>"Never <span>Giveup"</span></h1>
    <div class="matter">
        <ol type="I">
            <li><strong>WAKE UP AT 5:30 AM</strong></li><br>
            <li><strong>MEDITATION - 10MIN 5:30 TO 5:40AM</strong></li><br>
            <li><strong>FRESHUP - 10MIN 5:40 TO 5:50</strong></li><br>
            <li><strong>GYM - 1HR:30MIN ,6:00 TO 7:30</strong></li><br>
            <li><strong>BREAK FAST AND BATHING - 30MIN ,7:30 TO 8:00AM</strong></li><br>
            <li><strong>WORK - 2HRS ,8:00AM TO 10:00AM</strong></li><br>
            <li><strong>COLLEGE - 6HRS ,10:00AM TO 5:00PM</strong></li><br>
            <li><strong>SNACKS - 30MIN ,5:00PM TO 5:30PM</strong></li><br>
            <li><strong>WORK - 2HRS ,5:30PM TO 7:30PM</strong></li><br>
            <li><strong>SUPPER - 30MIN ,7:30 TO 8:00PM</strong></li><br>
            <li><strong>CHILL - 30MIN ,8:00PM TO8:30PM</strong></li><br>
            <li><strong>WORK - 1HR:30MIN ,8:30 TO 10PM</strong></li><br>
            <li><strong>DONOT FORGET TO SLEEP AT 10PM</strong></li><br>
        </ol>
        <h1>"(8+8+8)hrs Routine"</h1>
    </div>
    <div class="diet">
        <h2 class="heading">Pro<span>te</span>in</h2>
        <a href="    https://www.healthline.com/nutrition/high-protein-foods#chicken-breast" target="_blank">
        <h1 style="color: black;">Diet <br>Plan <br><span>TO</span><br> Look <br>Big</h1>
    </a>
        <div class="container">
            <div class="img-container">
                <img src="slide1.png" alt="Eggs" title="Eggs">
                <img src="slide2.png" alt="Chicken" title="Chicken">
                <img src="slide3.png" alt="Milk" title="Milk">
                <img src="slide4.png" alt="Peanut Butter" title="Peanut Butter">
                <img src="slide5.png" alt="Cheese" title="Cheese">
            </div>
        </div>
    </div>
</body>
</html>

# CSS FILE....

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: 'Josefin Sans' , sans-serif;
}
.zero{
    height: 100vh;
    width: 100%;
    background: url(backg.png);
    background-size: cover;
    background-position: center;
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between ;
    padding-top: 28px;
    padding-left: 10%;
    padding-right: 10%;
}

.logo{
    color: white;
    font-size: 28px;
}
h2 {
    text-align: start;
}
span{
    color:red ;
}
nav ul li{
    list-style-type: none;
    display: inline-block;
    padding: 10px 20px;
}
nav ul li a{
    color: white;
    text-decoration: none;
    font-weight: bold;
}
nav ul li :hover{
    color: red;
    transition: .3s;
}
button{
    border: none;
    background: red;
    padding: 12px 30px;
    border-radius: 30px;
    color: white;
    font-weight: bold;
    font-size: 15px;
    transition: .4s;
}
button:hover{
    transform: scale(1.3);
    cursor: pointer;
}
h1{
    margin: 0;
    padding: 0;
    text-align: center;
    font-size: 180px;
    position: absolute;
    top: 340px;
    left: 500px;
    transform: translateX(-50%) translateY(-50%);
}
.matter{
     background:url(wal.png);
     background-position: center;
     background-size: cover;
     text-align:end;
     font-size: large;
     color:white;
     padding-right: 5%;
     padding-top: 5px;
}
.matter h1{
    font-size: 160px;
    top: 950px;
    line-height: 160px;
    margin-left: -10px;
    color: transparent;
    -webkit-text-stroke: 1px #fff;
    background-image: url(rws.webp);
    background-size: cover;
    background-clip: text;
    -webkit-background-clip: text;
    background-position: 0 0;
    animation: back 20s linear infinite;
}
@keyframes back{
    100%{
        background-position: 2000px 0;
    }
}
.diet{
    min-height:  100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
}
.heading{
    font-size: 100px;
    padding-bottom :600px; 
    margin: auto;
    width: fit-content;
    align-items: flex-start;
}
.diet::before{
    content: '';
    background-image: url(prot.png);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    opacity: .5;
}
.diet h1{
    font-size: 110px;
    left: 90%;
    font-weight: lighter;
    font-stretch:ultra-expanded;
    text-shadow: black;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
.diet h1 span{
    font-size: 130px;
    font-weight: bold;
    font-stretch:ultra-condensed;
    text-shadow: black;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.container{
    width: 60vmin;
    position: absolute;
    top: 30px;
    left: 40%;
    transform: translate(-70%,20%);
    border: black;
    border-radius: 15px;
    box-shadow: 15px 25px 28px rgba(0, 92, 189, 0.785);
    overflow: hidden;
}
.img-container{
    width: 100%;
    display: flex;
    animation: slide 10s infinite;
}
img{
    width: 100%;
}
@keyframes slide {
    0%{transform: translateX(0);}
    25%{transform: translateX(0);}
    30%{transform: translateX(-100%);}
    50%{transform: translateX(-100%);}
    55%{transform: translateX(-200%);}
    75%{transform: translateX(-200%);}
    80%{transform: translateX(-300%);}
    100%{transform: translateX(-300%);}
}

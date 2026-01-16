
<html lang="en">
<head>
<meta charset="UTF-8">
<title>गोकर्ण जोशी घोडासैनी | Portfolio</title>

<style>


header{
    background: rgba(9, 78, 113, 0.9); /* slightly transparent */
    color:#040000;
    text-align:center;
    padding:40px 20px;
}
header h1{
    margin-bottom:10px;
    font-size:34px;
}
header p{
    font-size:18px;
}
button{
    padding:8px 16px;
    border:none;
    background:#ff9800;
    color:#fff;
    cursor:pointer;
    border-radius:5px;
    font-weight:bold;
    margin:5px;
}
button:hover{
    background:#e68900;
}
section{
    max-width:900px;
    margin:auto;
    padding:25px 20px;
    background: rgba(10, 122, 159, 0.9); /* slightly transparent */
    margin-top:20px;
    border-radius:8px;
}
h2{
    border-bottom:2px solid #111;
    padding-bottom:5px;
}
ul li{
    margin-bottom:6px;
}
.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:15px;
}
.card{
    padding:15px;
    background: rgba(249,249,249,0.9); /* slightly transparent */
    border-radius:8px;
    box-shadow:0 2px 5px rgba(0,0,0,0.1);
}
.social-links a{
    display:inline-block;
    margin:8px;
    padding:10px 18px;
    border-radius:25px;
    color:white;
    text-decoration:none;
    font-weight:bold;
}
.instagram{background:#E1306C;}
.facebook{background:#1877F2;}
.youtube{background:#FF0000;}
.email{background:#555;}
footer{
    margin-top:30px;
    background: rgba(17,17,17,0.9); /* slightly transparent */
    color:#fff;
    text-align:center;
    padding:15px;
}
</style>
</head>

<body>

<header>
    <h1>गोकर्ण जोशी घोडासैनी</h1>
    <p id="title">Actor | Model | Music Video Performer</p>

    <div class="lang-btn">
        <button onclick="setEnglish()">
            <img src="https://flagcdn.com/w20/us.png"> English
        </button>
        <button onclick="setNepali()">
            <img src="https://flagcdn.com/w20/np.png"> नेपाली
        </button>
    </div>
</header>

<section>
    <h2 id="aboutTitle">About Me</h2>
    <p id="aboutText">
        I am Gokarna Joshi Ghodasine, a passionate actor and model with strong camera presence.
    </p>
</section>

<section>
    <h2 id="careerTitle">Career Highlights</h2>
    <ul id="careerList">
        <li>Professional Actor & Model</li>
        <li>Featured in 4 Music Videos</li>
        <li>Strong camera-facing performance</li>
        <li>Comfortable with studio & outdoor shoots</li>
        <li>Dedicated to fitness & grooming</li>
    </ul>
</section>

<section>
    <h2 id="videoTitle">Music Video Experience</h2>
    <div class="cards">
        <div class="card">
            <iframe width="100%" height="200"
            src="https://www.youtube.com/embed/VIDEO_ID_1" allowfullscreen></iframe>
            <p id="video1">Music Video 1 </p>
        </div>

        <div class="card">
            <iframe width="100%" height="200"
            src="https://www.youtube.com/embed/VIDEO_ID_1" allowfullscreen></iframe>
            <p id="video1">Music Video 2 </p>
        </div>

        <div class="card">
            <iframe width="100%" height="200"
            src="https://www.youtube.com/embed/VIDEO_ID_1" allowfullscreen></iframe>
            <p id="video1">Music Video 3 </p>
        </div>

        <div class="card">
            <iframe width="100%" height="200"
            src="https://www.youtube.com/embed/VIDEO_ID_1" allowfullscreen></iframe>
            <p id="video1">Music Video 4 </p>
        </div>

    </div>
</section>

<section>
    <h2 id="skillsTitle">Skills</h2>
    <p id="skillsText">
        Acting, Modeling, Camera Facing, Expressions, Music Video Performance, Team Collaboration
    </p>
</section>

<section>
    <h2 id="contactTitle">Connect With Me</h2>
    <div class="social-links">
        <a href="https://facebook.com/gopal.joshi.376258" target="_blank">Facebook</a>
        <a href="https://instagram.com/gokarna_joshi_" target="_blank">Instagram</a>
        <a href="https://youtube.com/@janak_bhandari" target="_blank">YouTube</a>
        <a href="mailto:gokarnajoshighodasine3334@gmail.com">Email</a>
        
        <a href="https://tiktok.com/gokarnajoshi8427/" target="_blank">TikTok</a>
    </div>
</section>

<footer>
    <p id="footerText">© गोकर्ण जोशी घोडासैनी</p>
</footer>

<script>
function setEnglish(){
    document.title = "गोकर्ण जोशी घोडासैनी | Portfolio";

    document.getElementById("title").innerText="Actor | Model | Music Video Performer";
    document.getElementById("aboutTitle").innerText="About Me";
    document.getElementById("aboutText").innerText=
    "I am Gokarna Prasad Joshi Ghodasine, a passionate actor and model with strong camera presence.";
    
    document.getElementById("careerTitle").innerText="Career Highlights";
    document.getElementById("careerList").innerHTML=
    "<li>Professional Actor & Model</li>\
     <li>Featured in 4 Music Videos</li>\
     <li>Strong camera-facing performance</li>\
     <li>Comfortable with studio & outdoor shoots</li>\
     <li>Dedicated to fitness & grooming</li>";

    document.getElementById("videoTitle").innerText="Music Video Experience";
    document.getElementById("skillsTitle").innerText="Skills";
    document.getElementById("skillsText").innerText=
    "Acting, Modeling, Camera Facing, Expressions, Music Video Performance, Team Collaboration";
    document.getElementById("contactTitle").innerText="Connect With Me";
}

function setNepali(){
    document.title = "गोकर्ण  जोशी घोडासैनी | पोर्टफोलियो";

    document.getElementById("title").innerText="अभिनेता | मोडल | म्युजिक भिडियो कलाकार";
    document.getElementById("aboutTitle").innerText="मेरो परिचय";
    document.getElementById("aboutText").innerText=
    "म गोकर्ण  जोशी घोडासैनी हुँ, एक समर्पित अभिनेता तथा मोडल।";

    document.getElementById("careerTitle").innerText="करियर उपलब्धिहरू";
    document.getElementById("careerList").innerHTML=
    "<li>व्यावसायिक अभिनेता तथा मोडल</li>\
     <li>४ वटा म्युजिक भिडियोमा अभिनय</li>\
     <li>क्यामेराको अगाडि प्रभावशाली प्रस्तुति</li>\
     <li>स्टुडियो तथा बाहिरी सुटमा सहज</li>\
     <li>फिटनेस र ग्रुमिङमा समर्पित</li>";

    document.getElementById("videoTitle").innerText="म्युजिक भिडियो अनुभव";
    document.getElementById("skillsTitle").innerText="सीपहरू";
    document.getElementById("skillsText").innerText=
    "अभिनय, मोडलिङ, क्यामेरा फेसिङ, भावभंगिमा, म्युजिक भिडियो प्रस्तुति, टोलीसँग सहकार्य";
    document.getElementById("contactTitle").innerText="सम्पर्क गर्नुहोस्";
}
</script>

</body>
</html>

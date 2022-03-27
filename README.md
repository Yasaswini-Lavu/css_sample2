<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, intial-scale=1.0">
    <title>Personal Portfolio Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav class="navbar">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Portfolio</a></li>
            <li><a href="#">Education</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact </a></li>
        </ul>
    </nav>
    <section id="Home">
        <h1 class="heading">Hi,I am</h1>
        <h1 class="heading">PURI SAHITHYA</h1>
        <br></br>
        <p>AND THIS IS MY RESUME</p>
    </section>
    <section id="portfolio">
        <h1 class="heading">Portfolio</h1>
        <div class="gallery">
            <img src="image1.jpg" alt="">;
            <img src="image2.jpg" alt="">;
            <img src="image3.jpg" alt="">;
        </div>   
    </section>
    <section id="Education">
        <h1 class="heading">Education</h1>
        <div class="columns">
            <div class="box">
                <h2><center>Bachelors In Computer Science Engineering</center></h2>
            </div>
        </div>
        <center>
        <img src="college.jpg" height="10%" width="20%" alt="";
        </center>

    </section>
    <section id="About">
        <h1 class="heading">About Me</h1>
        <div class="About">
            <center>
            <img src="jenni.jpg" alt="">
            <div class="Name">
                <h2>I'm Puri Sahithya</h2>
            </div>
            </center>
        </div>
    </section>
    <section id="Contact ">
        <h1 class="heading">Contact </h1>
        <form action="" class="form">
            <input type="text" name="name" class="input" placeholder="Enter your Name">
            <input type="email" name="email" class="input" placeholder="Enter your email">
            <textarea name="message" id="message" cols="70" rows="20" placeholder="Enter Your Message">
            </textarea>
            <input type="submit" value="submit" id="submit">
        </form>
    </section>
        
</body>

</html>